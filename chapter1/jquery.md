# What is jQuery
jQuery is a JavaScript library. That means, it is built using JavaScript, it accepts Javascript methods and functions. 
But, jQuery can do more in a single line of code than JavaScript can do in a whole function. This shortens development time and let's face it, makes our jobs easier.

#What does jQuery look like?

```javascript
$(document).ready(function(){
//code here
});
```
The above snippet responds to the onready event. As with JavaScript, jQuery can respond to browser and input-output events.

What would this snippet do?
```javascript
$(document)ready(function(){
alert('This is an alert');
});
```

Now, let's add some jQuery to your page You will need two things:

1. jQuery from http://jquery.com/download

After you install jQuery into your application, add the following:

```javascript
$(document).ready(function(){
$('h1').css('display','none');
$('h1').fadein("slow");
});
```

Did the header 1 tag containing "Hello, World!" fade into the document?