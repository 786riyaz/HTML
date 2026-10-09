Heading Tag
Paragraph Tag
Image Tag
Anchor Tag
Button tag
Input Tag :: Input Types
Form Tag
Label Tag


Event and Event Handlers(Event Listener)


<img src="w3schools.jpg" alt="Schools Logo" width="250" height="400">
<p style="font-size:50px;">This is a paragraph.</p>
<body style="background-color:yellow; margin:0;">
<a href="https://www.google.com"> Click Here </a>
<label for="age"> Age : </label>
<input type="number" min="0" max="100" id="age" name="age">
Input Types ==> number, radio, text, email, tel, password, url, checkbox, date, time, datetime-local, week, month
<button type="submit"> Submit </button>
<button type="button" onclick="handleButtonClick()"> Greet </button>
Button Types ==> button, submit, reset
<script src="index.js"></script>
<textarea cols="30" rows="10"/>
<select><option>Hindi</option></select>

<form onSubmit="handleFormSubmit(event)" id="form">
<label for="name">Name:</label>
<input type="text" name="name" id="name">
<button type="submit">Submit</button>
</form>
function handleFormSubmit(event){
    event.preventDefault();
    console.log(event.target.name.value);
}