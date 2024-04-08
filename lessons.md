## HTTP Protocol

Http Protocol is the protocol that is used for transmitting data (files, images, videos, documents) between  a client and a server on the internet.
It follows the client-server achitecture : the client sends a request to the server, the server proccesses the request and returns a response. (Request Response Cycle).
It is a stateless protocal, meaning that each request from client to server is independent and unrelated to the previous request.
Http defines various methods that specify the action to be performed on a resource.
The most common Http methods are: GET, POST, PUT, DELETE.
Http also defines status codes that indicate the outcome of the requests. 

## HTML Form Element

An HTML Form element is an essential component of the web development, forms are used  used to collect user input and submit it to a server for processing. 
Here's an example of a form written in HTML:

<form action="/submit" method="post">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <button type="submit">Submit</button>
</form>


## JavaScript Core Objects

They are built-in objects provided by the JavaScript language itself.
Commonly used Javascript Core Objects: Object, Array, String, Number, Boolean, Function, Date, RegexExp, Math, Error

## JavaScript Scope and Inheritance

Javascript scope and inheritance are two important concepts in Javascript that defines how variables and objects are accessed and manipulated.

Scope is region of our code where a particular variable can be accessed.
There are Global Scope and Local Scope.
Variables declared outside of any function or block have global scope, meaning they can be accessed from anywhere in the code, including inside functions and blocks.
Variables declared inside of a function have a local scope, meaning they can only be accessed within that function.

Inheritance is a feature that allows a new object to inherit properties and methods from an existing object.


## JavaScript Module Pattern

Javascript Module Pattern is a design pattern used to encapsulate and organize code by creating modules.


## JavaScript Async Programming

Javascript asynchronous programming refers to programming paradigm that allows operations to be performed concurrently, without blocking the execution of the main thread. It is essential for performing handling tasks such as fetching data from servers and performing time-consuming computations.

In JavaScript, asynchronous programming is primarily achieved through the use of callbacks, promises, and more recently, async/await syntax.

## JavaScript Event Handlers

Javascript event handlers are functions executed in response to events triggered by user interactions or actions within a web page, such as clicking a button, hovering over an element, submitting a form, pressing a key, resizing the browser window.

## jQuery Library

jQuery is a fast, small, and feature-rich JavaScript library designed to simplify client-side scripting of HTML.
Its features include DOM manipulation and event handling, animation.

## Ajax and JSON

AJAX (Asynchronous JavaScript and XML) is a technique used in web development to send and receive data from a web server asynchronously without having to reload the entire web page.

JSON (JavaScript Object Notation) is a lightweight data interchange format. It is based on key-value pairs and supports arrays and nested objects.
Here's an example of JSON data:

{
  "name": "John Doe",
  "age": 30,
  "email": "john@example.com",
  "address": {
    "city": "New York",
    "country": "USA"
  },
  "hobbies": ["reading", "traveling", "photography"]
}


## Java Servlets

Java servlets are server-side Java components that handle HTTP requests and generate HTTP responses in Java web applications.

## Java Web Components

Java web components are the building blocks used in Java web applications for handling various tasks related to the presentation, processing, and management of web content. The main web components in Java EE (Java Enterprise Edition) are Servlets, JavaServer Pages (JSP), Filters, and Listeners.

## ES6 (Arrow Functions, Array API, Object Destructuring, Template Literals)

ES6 is an update to the Javascript language. It introduced new features and syntax.
Some key features include let,const, arrow functions, template literals, classes, enhanced object literals, destructuring assignments, default parameters, and the spread/rest operator.


## Promises

Promises in JavaScript are a way to handle asynchronous operations.
Here is an example of a Javascript Promise being used:

const myPromise = new Promise((resolve, reject) => {
    // Perform an asynchronous operation
    setTimeout(() => {
        const randomNumber = Math.random();
        if (randomNumber > 0.5) {
            resolve(randomNumber);
        } else {
            reject(new Error('Random number is less than 0.5'));
        }
    }, 1000);
});

## Servlets Filters

Servlets and filters are key components in JavaEE web applications.
Servlets are Java classes that handle requests from clients and generate responses dynamically.


## Servlets State Management

They are methods of techniques used to maintain the state or data associated with a user's interactions with web app across multiple requests.
Since HTTP is a stateless protocol, servlets need to employ various mechanisms to manage state for each user session. 
Several approaches to servlet state management:

HTTP session management, URL Rewriting, Hidden Form Fields, Cookies

## Java Servlets Server Pages (JSP)

JSP are HTML-like pages that contain embedded Java code, which is executed on the server-side to dynamically generate content.

## JSTL and Custom Tags

It is a collection of standard tags and functions that provide common functionality for JSP pages.
JSTL tags are prefixed with 'c:'.

Example of JSTL Core Tag being used:
<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
<c:if test="${user.loggedIn}">
    Welcome, ${user.username}!
</c:if>
