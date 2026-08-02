# dom.js 

    dom.js demonstrates how JavaScript interacts with the Document object Model(DOM) to access and manipulate HTML elements.Using DOM methods,JavaScript can change content,styles,attributes,and respond to user actions dynamically.

    Example:-
    JavaScript 

    const heading = 
    document.getElementById("title");
    heading.textContent = "Welcome to JavaScript";

    This code selects an HTML element with the ID title and changes its text content.

# get_elementby_id.js

    1.document.getElementById()
    2.Most commonly used DOM method.

# querySelector.js

    1.querySelector() and
    querySelectorAll()
    2.Modern and powerful element selection.

# getElebyClass_query...

    1.getElementsByClassName()
    2.getElementsByTagName()

# change_styles.js

    1.Changing CSS using JavaScript
    2.element.style

# iterate_elements.js

    1.Looping through multiple elements
    2.forEach(),for ... of


# dom_traversing.js

    DOM Traversing is the process of navigating between HTML elements in the DOM tree.JavaScript provides properties like parentElement,children,firstElementChild,and nextElementSibling to move through related elements.

    Example:-
    JavaScript

    const parent =
    document.getElementById("container");
    console.log(parent.children);

    This code accesses all child elements of the element with id "container".

# dom_tree.js

    A DOM Tree is a hierarchical structure of an HTML document where each element,attribute,and text is represented as a node.JavaScript uses this tree structure to access and manipulate web page content dynamically.

    Example:-
    JavaScript

    const body = document.body;
    console.log(body.children);

    This code accesses the <body> element and displays its child elements from the DOM tree.



    