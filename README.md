1. Emmet is an essential toolkit and plugin for text editors that lets web developers write HTML and CSS code much faster using short CSS-like abbreviations
2. A Content Delivery Network (CDN) is a group of connected servers spread across the world that work together to load web pages and internet content faster.
3. When we use React CDN links wrapped in the script tags, we have React injected inside it.
4. A react element at the end of the day is an object. When we render this object onto the DOM, it becomes an HTML element.
5. We are going to use webpack bundler for Namaste React.
6. We will be using "jest" for testing.
7. package.json: It is basically a configuration for our npm. The packages on which our project is dependent on are called "dependencies". npm takes care of the version of the dependecies. Npm does this taking care of the packages in the package.json file.
8. The most important package in our project is a "bundler" (e.g. webpack, parcel, vite). The job of a bundler is to package your app in such a way so that it can be shipped to a production. When we execute the command create-ract-app, it uses webpack behind the scenes.
9. In our project, we are going to use the "parcel" bundler.
10. We install parcel by executing the command npm install -D parcel. The "-D" means that it is a dev dependency. There are majorly two types of dependencies: Dev dependencies and normal dependencies. When we type -D it means that we are going to use that package during development.
11. In a package.json file the tilde/caret symbol tells the npm package manager to only allow the patch updates for a dependency.
12. Don't upload on Git what you can regenerate. Git should only have essential things.
13. npm means installing a package, while npx means executing the same package.
14. Using CDN links is not a preferred way to bring React into your project.
15. The core difference is that package.json defines the intended configuration and flexible version ranges for your project's dependencies, while package-lock.json locks down the exact, specific versions of every package and sub-dependency actually installed to ensure identical environments across different machines
16. The node_modules folder in a React project is a local directory where npm or yarn downloads and stores all third-party packages, libraries, and their underlying dependencies required to build and run your application
17. Parcel also does HMR (Hot Module Replacement) for you. Parcel uses a file watching algorithm in c++ in order to execute HMR.
18. Parcel also image optimization for you. Uploading images in web browser is the most expensive performance in the browser.
19. Parcel also minification when you do a production build. Parcel also does differential bundling for us. When you execute the command npx parcel build index.html it bundles all the files in the dist folder.
20. JSX is a javascript syntax which makes it easier to create React elements.
21. A js engine understands ecmascript. Even thought the js engine can't understand JSX, it still gets executed perfectly because parcel is doing the translation behind the scenes. The entire JSX code is transpiled before it goes to the js engine. The transpiling is done by a a package by the name of "babel".
22. Babel is a compiler/transpiler that translates new ES6 code or React code into older version of javascript code which older browsers can understand.
23. There are two types of React components: Class based components and Functional components. Class based components are the old way to create react components while functional components is the new way to create react components. Class based components use javascript classes while functional components use javascript functions to create components.
24. Writing javascript inside of JSX is a powerful feature of React.
25. Functional Component: It is a javascript function that accepts inputs and returns JSX to describe a user intereface. If you write curly braces anywhere inside functional component in react, you can use pure javascript code. JSX is not HTML. JSX stands for Javascript XML which is HTML like syntax.
26. When you create a React app, the first major step is to create a design mock so that you are clear about the layout of your website.
27. In react, there is a feature named "props". Props is the short form for properties. Properties can be passed to a component. Props, at the end of the day are arguments to a javascript function. Passing a prop to a component is like passing an argument to a function. In react, when you have to dynamically pass some data in a component, you pass the data as a prop.
28. "Config driven UI". This is done because our websites are driven by data a.k.a "configs". Controlling how your UI looks like using data is called config driven UI.
