# Phoeurn_Rozariya_W04_Lab4
Javascript Lab 4
To change the content in html:
<p id="demo">Hello</p>

<script>
// Access a paragraph Element
const myPara = document.getElementById("demo");

// Change the content of the Element
myPara.innerHTML = "Hello World!";
</script>
Or 
document.getElementById("demo").innerHTML = "Date : " + Date();
To get content:
Let a = document.getElementById("demo").innerHTML

To get or change value in form:
<input type="text" id="fname" size="20" name="fname">
let fname = document.getElementById("fname").value;
document.getElementById("fname").value ="dara";


Function: 

<button onclick="myFunction()">Click me</button>

<p id="demo"></p>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello World";
}
</script>

Popup:
Alert:
alert("I am an alert box!");
	Confirm:
<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  var txt;
  if (confirm("Press a button!")) {
    txt = "You pressed OK!";
  } else {
    txt = "You pressed Cancel!";
  }
  document.getElementById("demo").innerHTML = txt;
}
</script>

Prompt Box:

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  let text;
  let person = prompt("Please enter your name:", "Harry Potter");
  if (person == null || person == "") {
    text = "User cancelled the prompt.";
  } else {
    text = "Hello " + person + "! How are you today?";
  }
  document.getElementById("demo").innerHTML = text;
}
</script>

Exercise: 

Write a simple JavaScript program to find whether a given year is a leap year or not. The user will provide the year by prompt.

Write a simple JavaScript program to join all elements of the following array into a string by using for loop.
Sample array : myColor = ["Red", "Green", "White", "Black"];
Expected Output : "Red,Green,White,Black"

The new Date() constructor creates a new Date object.

getDate()	Returns the day of the month (from 1-31)
getDay()	Returns the day of the week (from 0-6)
getFullYear()	Returns the year
getHours()	Returns the hour (from 0-23)
getMilliseconds()	Returns the milliseconds (from 0-999)
getMinutes()	Returns the minutes (from 0-59)
getMonth()	Returns the month (from 0-11)
getSeconds()	Returns the seconds (from 0-59)

Example: const d = new Date();
let hour = d.getHours();

	Write a JavaScript function to say “Good Morning”, or “Good Afternoon” or “Good
Evening” according to current time.

In cryptography, a Caesar cipher, also known as Caesar's cipher, the shift cipher, Caesar's code or Caesar shift, is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet.
The transformation can be represented by aligning two alphabets; the cipher alphabet is the plain alphabet rotated left or right by some number of positions. For instance, here is a Caesar cipher using a left rotation of three places, equivalent to a right shift of 23 (the shift parameter is used as the key): 
 
Plain:    ABCDEFGHIJKLMNOPQRSTUVWXYZ
Cipher:   XYZABCDEFGHIJKLMNOPQRSTUVW
 

Encrypt:
 
Encode the message using shift Caesar cipher technic:
Example: $str = “Hello world!.”;
        	$shift=3;
The cipher text is: “Khoor zruog!”
 
Decrypt: 
 
Decode the message using the same technic of group1:
Example Cipher text = “Khoor zruog!”;
        	$shift = 3;
        	message: “Hello world!”;

Write JavaScript to allow the user to put the text for encrypt and decrypt. The interface should be used with tailwindcss with daisyui.
Build-in function:
String.fromCharCode(): To convert ASCII number to character
Example: String.fromCharCode(65); // A
charCodeAt(0): To convert char to ASCII number.
Example: char = ‘A’;
char.charCodeAt(0) // 65
document.getElementById("ID").value // To get value from input
document.getElementById("ID").textContent = “This is testing” // To set text to div or p
<button onclick="function_name()">Encrypt</button> // To call to javascript function



