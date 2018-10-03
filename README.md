# mean-example
MEAN example from Academind

Application to create, edit, delete posts.

## Angular
A Client-Side (browser) Framework which allows you to build Single-Page-Applications (SPA)

* Render UI with Dynamic Data
* Handle User Input
* Communicate with Backend Services

Provides a "Mobile App"-like User Experiencce.

## Node
A Server-side Library: JavaScript on the Server-side

* Listen to Requests and Send Responses
* Execute Server-Side Logic
* Interact with Databases and files

An alternative to PHP, Ruby on Rails, Java, etc. Is rarely used standalone!

## express
A Node framework wich simplifies writing Server-side code and logic.

* Based on Node, offers same functionalities
* Middleware-based: funnel requests through Functions
* Includes Routing, View-rendering & More

Simplifies the usage of Node. Express is for Node what Laravel would be for PHP.

## mongoDB

A NoSQL Database which stores "Documents" in "Collections" (instead of "Records" in "Tables" as in SQL).

* Store Application Data (Users, Products, ...)
* Enforces no Data Schema or Relations
* Easily connected to Node/Express (NOT to Angular!)

A powerful Database which can easily be integrated into a Node/express environment.

## What is a Single Page Application?

Allows for instant re-rendering, instant user feedback and makes building highly engaging UIs possible.

## How does the MEAN work?

### Client (Browser)

* Angular
* Presentation/UI
* Single-Page-Application (not necessarily server by Node backend)

### Server

* Node + express + mongoDB
* Bussiness Logic
* Persistent Data Storage
* Authentication Logic

The client and the server communicate with requests/responses using JSON data format. AJAX (Background)

## Outline

* Getting Started
* Angular Frontend
* Node.js + Express Backend
* Handling Data with MongoDB
* Enhancing the App
* Image Upload
* Data Pagination
* Authentication
* Authorization
* Error Handling
* Optimizations
* Deployment

## The Angular Frontend

### Understanding Angular Components

* Angular Thinks in "Components"

### 14 - Listening to events

* Event binding `(click)="onMethod()"`

### 15 - Outputting Content

* String interpolation of method/property `{{ property/method }}`
* Property binding `[value]="code"`

### 16 - Getting user input

* Local reference `#postInput`