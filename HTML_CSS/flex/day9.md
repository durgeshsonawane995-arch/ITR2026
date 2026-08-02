1_dot_bracket.js

dot_bracket.js demonstrates two ways to access and modify object properties in JavaScript:

Dot Notation (.) – Used when the property name is a valid identifier.
Bracket Notation ([]) – Used when the property name contains spaces, special characters, or when the property name is stored in a variable.

Example:
let person = {
  name: "Durgesh",
  age: 20,
  "phone number": "9876543210"
};

// Dot notation
console.log(person.name);   // Durgesh

// Bracket notation
console.log(person["phone number"]); // 9579264611

// Using variable
let key = "age";
console.log(person[key]);   // 20

Output:
Durgesh
9876543210
20

# 2_computed_properties.js
Computed Properties allow you to create object property names dynamically using variables or expressions inside square brackets [].

Example:
let key = "email";

let user = {
  name: "Durgesh",
  [key]: "Durgesh@gmail.com"
};

console.log(user);

Output:
{
  name: "Durgesh",
  email: "Durgesh@gmail.com"
}

# 3_intro_Objects.js
An Object in JavaScript is a collection of key-value pairs used to store related data. Each key is called a property, and its associated value can be of any data type (string, number, boolean, array, function, etc.).

Example:
let person = {
  name: "Durgesh",
  age: 20,
  city: "Pune"
};

console.log(person);

Output:
{
  name: "Durgesh",
  age: 20,
  city: "Pune"
}

# 4_iterate_objects.js
Iterating an object means accessing all its properties one by one. The for...in loop is commonly used to loop through an object's keys.

Example:
let person = {
  name: "Durgesh",
  age: 20,
  city: "Pune"
};

for (let key in person) {
  console.log(key, ":", person[key]);
}

Output:
name : Durgesh
age : 20
city : Pune

# 5_nested_destructuring.js
Nested Destructuring is used to extract values from nested objects or arrays into separate variables in a single statement.

Example:
let user = {
  name: "Durgesh",
  address: {
    city: "Pune",
    state: "Maharashtra"
  }
};

let {
  name,
  address: { city, state }
} = user;

console.log(name);
console.log(city);
console.log(state);

Output:
Yash
Pune
Maharashtra

# 6_object_inside_array.js
An array of objects is an array where each element is an object. It is commonly used to store multiple records, such as students, employees, or products.

Example:
let students = [
  { name: "Durgesh", age: 20 },
  { name: "Rahul", age: 21 },
  { name: "Amit", age: 22 }
];

console.log(students[0].name); // First student's name

for (let student of students) {
  console.log(student.name, student.age);
}

Output:
Durgesh
Durgesh 20
Rahul 21
Amit 22

# 7_spread_operator.js
The Spread Operator (...) is used to expand the elements of an array or the properties of an object. It is useful for copying, merging, and passing multiple values.

Example:
let arr1 = [1, 2, 3];
let arr2 = [...arr1, 4, 5];

console.log(arr2);

Output:
[1, 2, 3, 4, 5]