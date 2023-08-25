# Js-HomeAssignment-09

This is a simple HTML, CSS, and JavaScript code that allows a user to add paragraphs to a webpage

hosted link : https://ganeshdhaygude.github.io/Js-HomeAssignment-09/

Step-by-Step Explanation

HTML

The HTML code creates a simple webpage with a text input, a button, and a div to hold the paragraphs.

<title>Document</title>
Add
<script> JavaScript</script>


The JavaScript code adds a new paragraph to the webpage when the "Add" button is clicked.

const Button = document.getElementById('addButton'); const text = document.getElementById('text'); const paragraph = document.getElementById('paragraph');

Button.addEventListener('click', () => { const newText = text.value;
const newParagraph = document.createElement('p'); newParagraph.textContent = newText; paragraph.appendChild(newParagraph); text.value = ''; });
