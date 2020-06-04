# Simple Javascript library like Jquery

## Getting started

Add lib.js in your html page and start using the lib methods. Also, can extend the lib.js methods as desired!!


## Usage
```javascript
<script src="lib.js" ></script>

// get HTML of element
console.log('html  ',$('h3').html());

// get ID
console.log('ID  ',$('h3').getId());

## get innerText
console.log('Inner Text  ',$('h3').getText());

## add events
$('h3').on('click',() => {
    alert('clicked!');
});

// hide element
$('h3').hide();

// show element
$('h3').show();

// get or set attribute
$('h3').attr('class','redh3');

// remove attribute
$('h3').removeAttr('class');

// set backround
$('h3').setBackground('red');

// remove background
$('h3').removeBackground();

// set color
$('h3').setColor('red');

// remove color
$('h3').removeColor();

```

## Happy coding!!
