# dom_createEle.js

    createElement() is a DOM method used to create a new HTML element dynamically using JavaScript.After creating the element,It can be added to the webpage using methods like appendChild().

    Example:-
    JavaScript

    let para = document.createElement("p");
    para.innerText = "Hello World!";
    document.body.appendChild(para);

    Output:-
    A new paragraph with the text "Hello World!"is added to the webpage.

# Change Background Color in JavaScript

    The backgroundColor property is used in JavaScript to change the background color of an HTML element or the entire webpage dynamically.It is accessed through the style object of an element.

    Example:-
    JavaScript 

    // Change the background color of the webpage
    document.body.style.backgroundColor = "lightblue";
    
    Output:-
    The Webpage background color will change to light blue.

# FilterFruits in JavaScript 

    The filter() method is used to create a new array containing only the elements that satisfy a given condition.It does not modify the original array.

    Example:-
    JavaScript

    let fruits = ["Apple","Banana","Mango","Orange"];
    let result = fruits.filter(fruit => fruit.startsWith("A"));

    console.log(result);

    Output:-
    JavaScript

    ["Apple"]

    Here,filter() returns only the fruits whose names start with "A".

# Responsive_Navbar.js 

    A Responsive Navbar is a navigation menu that adjusts automatically to different screen sizes.JavaScript is used to show or hide the menu when the user clicks a menu button(hamburger icon).

    Example:-
    JavaScript

    function toggleMenu() {
        let menu = document.getElementById("navbar");
        menu.ClassList.toggle("active");
    }

    Output:-
    When the menu button is clicked,the navigation menu is shown or hidden,making the navbar responsive on mobile devices.

# Slider in JavaScript 

    A slider in JavaScript is used to display multiple images or content one by one.Users can navigate through items using buttons,arrows,or automatic transitions.

    Example:-
    JavaScript

    let images = ["img1.jpg","img2.jpg","img3.jpg"];
    let current = 0;

    function nextSlide(){
        current = (current + 1) % images.length;
        console.log(images[current]);
    }

    Output:-
    Each time nextSlide() is called,the next image in the slider is displayed.

# Text_Size_Changer.js 

    A text size changer in JavaScript is used to increase or decrease the font size of text dynamically.It uses the style.fontSize property to modify the size of an HTML element.

    Example:-
    JavaScript

    let text = document.getElementById("para");
    text.style.fontsize = "24px";

    Output:-
    The font size of the element with id = "para" changes to 24 pixels.
