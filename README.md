# Browser
Difference between HTTP 1.1 and HTTP 2 and JS object internal representation

## HTTP 1.1
<p>Developed by Timothy Berners-Lee in 1989 as a communication standard for the World Wide Web, HTTP is a top-level application protocol that exchanges information between a client computer and a local or remote web server. It was introduced to improve the performance and do the basics for standard requests such as GET, HEAD, PUT and POST.HTTP 1.1 allows one outstanding request per TCP connection. It does multiple requests to be pipelined. This standard application protocol exchanges information between a client computer and a remote web server. The client sends a text based request to the server like GET or POST. These requests and responses will go back and forth multiple times until all the elements or contents of a webpage are delivered to the client computer. This caused the slow loading of webpages, loading of redundant data and lack of user experience.</p>

## HTTP 2
<p>HTTP/2 began as the SPDY protocol, developed primarily at Google with the intention of reducing web page load latency by using techniques such as compression, multiplexing, and prioritization. This protocol served as a template for HTTP/2 when the Hypertext Transfer Protocol working group httpbis of the IETF (Internet Engineering Task Force) put the standard together, culminating in the publication of HTTP/2 in May 2015. From the beginning, many browsers supported this standardization effort, including Chrome, Opera, Internet Explorer, and Safari. Due in part to this browser support, there has been a significant adoption rate of the protocol since 2015, with especially high rates among new sites.</p>
<p>HTTP 2 helped to improve the online experience with faster Speed, improved user experience and reduced latency using binary protocols, Multiplexing, header compression, server push and increased security.</p>


## Object internal represetation in JavaScript.

<p>Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript.</p>
<h3>Object in JS</h3>
<p>Objects are the one of the data types in javascript. It is defined as  “reference data type”. When a value is assigned to an Object variable it becomes a reference value which points towards the memory where the value is stored. In this case, the variables don't actually store a value.</p>
<p>An object is declared in javascript as :</p>

```javascript
var objectName = {
  key1: value1,
  key2: value2
  }
```
<p>An example of an object in javascript</p>

```javascript
var person = {
name: "Rajesh",
age: 30,
gender: "M"
}
```

<p>An object with key: value pairs often called as the properties of the object. The properties can be accessed in following ways. </p>
<li>using dot notation (.)</li>
<li>using bracket notation ([])</li>

<p>An example of each notation is given below.</p>

<li>Example of dot notation</li>

```javascript
var person = {
name: "Rajesh",
age: 30,
gender: "M"
}

console.log(person.name) // Rajesh
```
<li>Example of bracket notation</li>

```javascript
var person = {
name: "Rajesh",
age: 30,
gender: "M"
}

console.log(person["name"]) // Rajesh
```
