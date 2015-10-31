# SocketStream

> The Future is Real Time

## Introduction

SocketStream is a framework for real-time, single-page web applications.

(Click here for the Quick Start guide.)

SocketStream is comparable to other real-time frameworks such as [Meteor](https://www.meteor.com/), [Sails](http://sailsjs.org/), and [Derby](http://derbyjs.com/), but distinguishes itself by offering well-organized interoperability with other packages in the Node.js ecosystem, and favoring flexible <!--TO COME: but well-documented--> coding practices over strict convention.

With traditional HTTP websites, users refresh pages to display new information. With a simple WebSocket handshake, SocketStream ports precompiled HTML templates, CSS, and JavaScript (dynamic or reactive), in a single payload, and then keeps the subscribed connection open for additional PubSub requests and responses. No polling. No AJAX. Just event-driven, streaming data.

### A Feel-good Approach

SocketStream sits comfortably between loose approaches like Express + Socket.io and opinionated approaches such as Meteor or Firebase. It provides tools to help build single page apps, but tries not to restrict what technologies you can use with your app. For example, SocketStream does not:

* Provide an ORM. You choose the database and modeling conventions.
* Mandate a specific client-side framework. Feel free to use React, Angular, Ember, Ractive, or anything suited to your needs.
* Mandate language preprocessors. Use Jade, Handlebars, Stylus, Less, CoffeeScript. Again, we try to get out of your way.
* Enforce an isomorphic environment. That's up to you. SocketStream definitely has an out of the box solution, but how you structure things from there out is (largely) up to you.

### What SocketStream Does

So what does SocketStream do? Here are some of the basics, but we'll go into depth on each one further in the documentation.

* HTML/CSS/JS code preprocessers
* Live reload (development)
* CSS/JS compilation and CDN asset pipeline management
* WebSocket management
* RPC APIs
* PubSub APIs
* Client-side code organization
* Session management (defaulted to REDIS)
* Custom WebSocket APIs
* HTML Templates (custom or default)
* Web Workers
* Compatibility with Connect Middleware

Before we get into the nuts and bolts, however, let's get started.
