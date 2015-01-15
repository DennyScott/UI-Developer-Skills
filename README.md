#UI Developer Skills

##Frameworks

###Angular
MV* Framework to build mobile apps with

###Famous
View Framework to help build apps with. We use this to build native-like animations. Uses Matrix3D transformation, so the elements on the page are GPU(hardware)-Accelerated. Furthermore, famous renders the dom itself through its own engine. This means we don't have to use JQuery to query the DOM, we already have the items in Javascript.

###Ionic
Framework built with Angular JS. Similar to bootstrap functionality, but written in the "Angular" way, using Directives and allowing for more semantic (declaritive) html.

###Bootstrap
Sometimes we use it. A front-end framework used for styling.

###Backbone
Backbone.js gives structure to web applications by providing models with key-value binding and custom events, collections with a rich API.

##Build Tools

### Gulp: 
Gulp is a fast and intuitive streaming build tool built on Node.js. It's used for building tasks, such as building, minification, testing, etc. Gulp uses Javascript, allowing functions for tasks.

### Grunt
Similar to Gulp, but uses Object notation.

### Lineman
is a command-line utility that is hyper-focused on helping web developers build first-class JavaScript web applications. Dependent on Grunt.


## Package Management Systems

### Bower
Bower offers a generic, unopinionated solution to the problem of front-end package management, while exposing the package dependency model via an API that can be consumed by a more opinionated build stack.

### NPM
npm is a package manager for JavaScript, and is default for Node.js.

### Yeoman
Yeoman helps you to kickstart new projects, prescribing best practices and tools to help you stay productive. Allows us to Scaffold Projects.

## Mobile Deployment

### Cordova
Apache Cordova is a set of device APIs that allow a mobile app developer to access native device function such as the camera or accelerometer from JavaScript

### Cocoon JS
For our purposes, allows us to wrap a newer browser dependency with apps then Cordova. This will speed up our app under the hood, since the newer browsers generally allow faster compiling.

### Phonegap 
Cordova, but owned by Adobe. Has some streamlining.


## Front-End Libraries

### Lo Dash / Underscore
A utility library delivering consistency, customization, performance, & extras.

### JQuery
We don't use this too much, as parsing dom is expensive on mobile, regardless, it's still very important to know. a cross-platform JavaScript library designed to simplify the client-side scripting of HTML

### Parse
add a powerful core, push notifications, and analytics to your app with Parse. 


## Testing Libraries

### Karma
A simple tool that allows you to execute JavaScript code in multiple real browsers. Used as a test runner for our Jasmine tests.

### Jasmine
Behavior-driven development framework for testing JavaScript code. It does not depend on any other JavaScript framework. It does not require a DOM.

## Style Frameworks

### SASS
Sass is a scripting language that is interpreted into Cascading Style Sheets (CSS). SassScript is the scripting language itself.

### LESS
Less extends CSS with dynamic behavior such as variables, mixins, operations and functions.

## Backend Systems

### Node JS
Node.js is an open source, cross-platform runtime environment for server-side and networking applications. Node.js applications are written in JavaScript, and can be run within the Node.js runtime on OS X, Microsoft Windows, Linux and FreeBSD.

### Express
Express is a minimal and flexible Node.js web application framework

### Sails
Sails.js make it easy to build custom, enterprise-grade Node.js apps. It is designed to mimic the MVC pattern of frameworks like Ruby on Rails

### Rails
Rails is a full-stack framework that emphasizes the use of well-known software engineering patterns and paradigms, including convention over configuration (CoC), don't repeat yourself (DRY), the active record pattern, and model–view–controller (MVC).


## Database
### Mongo DB
an open-source document database, and the leading NoSQL database.
### My SQL
SQL Database. Most Popular.


## Game Engines
### Unity
Unity is a cross-platform game creation system developed by Unity Technologies, including a game engine and integrated development environment (IDE). It is used to develop video games for web sites, desktop platforms, consoles, and mobile devices.

### Phaser
A free, fast and flexible framework for HTML5 game creation. Uses Web GL with a Canvas Fallback. Basically a Game Engine built on top of Pixi JS.

### Pixi JS
The aim of this project is to provide a fast lightweight 2D library that works across all devices. The Pixi renderer allows everyone to enjoy the power of hardware acceleration without prior knowledge of webGL. Also, it's fast.

### CreateJS
Canvas Html5 Game Engine. A library of systems: EaselJS, TweenJS, SoundJS

<hr>


## Questions
### What are the differences between Web Gl and Canvas?
Canvas allows for dynamic, scriptable rendering of 2D shapes and bitmap images. WebGL is a JavaScript API for rendering interactive 3D graphics and 2D graphics within any compatible web browser without the use of plug-ins. WebGL allows for hardware acceleration.

### What is the scope in Angular?
Scope is the glue between application controller and the view. Data passed in the Scope can be used in both the view and the model.

### What are the benefits to Web GL?
WebGl allows for both 3D graphics, used OpenGl Web under the hood, and allows for hardware acceleration.

### What is the purpose of Hardware(GPU) Acceleration?
Hardware acceleration is the use of computer hardware (the GPU) to perform some functions faster than is possible in software running on a more general-purpose CPU

### Can you give some details about Agile Methodologies (Scrum/Kanban)
* Scrum
  * Scrum is an iterative and incremental agile software development framework for managing product development. 
  * Velocity
  * Planning Poker
  * Stories
  * Backlog
* Kanban
  * Kanban is a method for managing knowledge work with an emphasis on just-in-time delivery while not overloading the team members.
  * Stories

### What is TDD?
Test-driven development (TDD) is an advanced technique of using automated unit tests to drive the design of software and force decoupling of dependencies.

### Have you ever tried Object-Oriented Javascript? What were your experiences like?
Open Answer

### Scenario: A backend Developer has completed his REST API for your app. What does that mean?
REST is an architecture style or design pattern used as a set of guidelines for creating web services which allow anything connected to a network. This mean the developer has completed a server for us, where we can now Update Post Insert and Remove data from.

### Whats Faster for Animations? Javascript or CSS? Why?
Either argument has it's valid points. Javascript can technically faster as long as it uses CSS3 Transformations under the hood and specifically targets the hardware. If anyone says JQuery is faster, they're way off. If they mention that CSS 3 is faster then Jquery Animations, that is correct!

### Scenario: You've grabbed a story from the backlog, and started you first task. You opened your text editor, and are ready to start the feature. What are your first steps?
Open Answer

### What is Local Storage used for?
With local storage, web applications can store data locally within the user's browser.

### What are Private, Privlliged and Public functions in Javascript?
Private Functions are functions wrapped in a closer and only usable within that function.

Privlliged functions can be called publicly, but can also call the private functions within their home function.

Public functions are connected to an object through its prototype and cannot call an objects private functions.

### What are services used for in Angular?
Angular services are substitutable objects that are wired together using dependency injection (DI). You can use services to organize and share code across your app.

### Why would you develop an App with HTML 5? 
Many reasons, one code base and common HTML 5 familiarity being the largest reasons

### When developing in HTML 5, how would you deploy the app to:
* **Mobile**
  *  Use Cordova 
* **Web**
  *  Should deploy as is, by spinning up a server. 
* **Desktop**
  * You could use Node-Webkit to handle this. 

### What is the window namespace used for in Javascript?
Global Variables.

### What is Isomorphic Javascript?
Frameworks that mix the Server and Client side Code. Ember Js, Meteor, etc.

### What sort of features are coming in ECMAScript 6?
Classes, Modules, Syntax Sugar, etc.

### What is the Box Model?
Box model is essentially a box that wraps around HTML elements, and it consists of: margins, borders, padding, and the actual content.

### Why can JQuery be bad for mobile?
Dom Parsing is heavy for the CPU. On desktops, this is virtually not noticable. On Mobile though, this can chug the Mobile.

### How would you make an app feel/perform more Native?
Open Answer. Animations, Performance, Movement, Velocity, Famous, CSS Transformations.

### Whats the major differences between HTML 5 and Native Apps?
HTML 5 is a code once, run anywhere platform. They run on a web browser on the mobile device. Native has been specifically coded for that device. It has better access to the hardware, and doesn't require the overhead of a browser, but will not run on other devices.

### What is the difference between Skeumorphism and Flat Design?
* Skuemorphic
  * emulates the aesthetics of physical objects.
* Flat
  * a style of interface design which removes any stylistic choices that give the illusion of three-dimensions. Minimalist

### What is Material Design?
Google Design. Material has physical surfaces and edges. Seams and shadows provide meaning about what you can touch.

### Scenario: Your project manager has asked you to start a new HTML 5 App. What are your first steps?
Open Answer

### What is DRY?
Don't Repeat Yourself.

### Scenario: A designer has handed you a new design for a web app, how do you begin moving the design to concept?

### What is a full stack developer?
a Full Stack Developer is someone with familiarity in each layer, if not mastery in many and a genuine interest in all software technology.

### What are the benefits of using a "Prebuilt" framework, like bootstrap and ionic, to something like Famous and Backbone?

Open Answer. Basically, framework already has commonly used "widgets" or functions, reducing the development time.

### Scenario: Your designer has handed you an mobile app design with light transitions between pages, how would you handle these animations?
Open Answer

### How comfortable are you with Github? Do you have personal projects? Have you contributed to anything we can see publicly?
Open Answer

### Name your faviourite javascript library, and why.
Open Answer

