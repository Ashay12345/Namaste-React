1. The first step is where we learn how to use CDN links and inject react in the HTML file.
2. A CDN or a Content Delivery Network is a group of connected servers spread across the world that delivers web content closer to users to speed up loading time.
3. React CDN gives the abilities of React and helps us render components on to the DOM directly using React.
4. React.createElement takes three attributes (the element, an object, what you want to display on the DOM)
5. React.render helps in rendering whatever you want on the DOM
6. The most costly operation is when there are changes in the DOM display and the DOMtree is getting changed in the backend.
7. A react element is nothing but a javascript object.
8. The "render" basically converts this object into an H1 tag and displays it on the DOM.
9. npm (officially standing for Node Package Manager) is the default package manager and online registry for JavaScript and Node.js.
The 'package.json' file is a configuration for our npm. NPM basically takes care of all the packages or dependencies or project is dependent on in the package.json file.
The most important package in our React project is a bundler.
A "bundler" is a development tool that bundles all your source files of your react project into a single "bundle" so that the web browser can easily read it and execute it.
There are two types of dependencies: a. The Dev Dependencies and b. The Normal Dependencies. when we type the command "npm install parcel" the terminal downloads the parcel bundler from the npm website.
The package-lock.json in an automatically generated file in Node.js projects that records the exact, locked versions of every installed package. Basically, package.json maintains a track of all approximate versions of all the packages and pacakge-lock.json keeps a track of all the accurate versions of all the packages.
If you have package.json and package-lock.json, you can regenerate node_modules folder. Do not upload on git whatever you can regenrate. Git should only have essential things.
When you type the command "npx parcel {package-name}" you execute a package.
CDN links are not the ideal way to bring react into your -project.
When you type "import React from 'react'" in any file, you basically import the react package from the node_modules folder.
