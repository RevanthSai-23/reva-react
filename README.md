Episode 1 : 

1 - Emmet is a free addon for the text editorthat allows us to type shortcuts are then expanded full piece of code

2 - When an application code uses a library, the developer writing the code is in charge of the application flow. This means the developer decides when to call the library. However, when we use a framework, the framework decides when to call the library. This shift in control of calling the library from the application code to the framework is an inversion of control. A library is a collection of reusable, compiled, and tested code that can facilitate the automation or augmentation of application functionalities. It’s designed to support both the code developer and code compiler during the build process and the running of the application. A library implements many functions, variables, and parameters.
A framework is used for building and deploying an application quickly. When we use a framework, we can use resources to facilitate faster development and a greater user experience. A library is used to enhance the functionality of an application. If we develop our own library, we can use the functions in many applications.


3 - A content delivery network (CDN) is a network of interconnected servers that speeds up webpage loading for data-heavy applications. CDN can stand for content delivery network or content distribution network. When a user visits a website, data from that website's server has to travel across the internet to reach the user's computer. If the user is located far from that server, it will take a long time to load a large file, such as a video or website image. Instead, the website content is stored on CDN servers geographically closer to the users and reaches their computers much faster.

4 - React is called "React" because of its core feature, which is its ability to "react" or respond dynamically to changes in data. And it’s called React because it reacts. It was developed by Facebook (a site that CONSTANTLY updates their data) to improve the user interface development and more effectively change (REACT to) what the user sees when they’re doing things like mouse clicking, submitting and typing.”

6 - React is a JavaScript library for building User Interfaces and ReactDOM is the JavaScript library that allows React to interact with the DOM. ReactDOM is the glue between React and the DOM.

7 - It is expected that you use the development mode when working on your app, and the production mode when deploying your app to the users.


Episode - 2 :

2 - Webpack is a static module bundler for JavaScript applications — it takes all the code from your application and makes it usable in a web browser. Modules are reusable chunks of code built from your app’s JavaScript, node_modules, images, and the CSS styles which are packaged to be easily used in your website. Webpack separates the code based on how it is used in your app, and with this modular breakdown of responsibilities, it becomes much easier to manage, debug, verify, and test your code.

--> Parcel and webpack are the bundlers used mostly for JavaScript or Typescript code that helps you to minify, clean, and make your code compact so that it becomes easier to send a request or receive the response from the server when it usually takes you to transfer multiple files without using any bundler for loading the page of your application.

3 - The .cache folder stores information about your project when parcel builds it, so that when it rebuilds, it doesn't have to re-parse and re-analyze everything from scratch. It's a key reason why parcel can be so fast in development mode.

4 - The NPX stands for Node Package Execute. It can also be called the npm package runner that can execute packages that you want from the npm registry without installing it locally.

5 - Dependencies are used for production or in testing environments. Whereas devDependencies are used for project development purposes only.

6 - Hot Module Replacement (HMR) exchanges, adds, or removes modules while an application is running, without a full reload. This can significantly speed up development in a few ways:

Retain application state which is lost during a full reload.
Save valuable development time by only updating what's changed.
Instantly update the browser when modifications are made to CSS/JS in the source code, which is almost comparable to changing styles directly in the browser's dev tools.

7 - The “package. json” file defines the rules required to run your application and install dependencies. On the other hand, the “package-lock. json” file holds detailed information on all the dependencies installed based on the package.

8 - The /dist stands for distributable.
The /dist folder contains the minimized version of the source code.
The code present in the /dist folder is actually the code which is used on production web applications.

9 - A node_modules directory contains all the React dependencies packages: react , react-dom , and their transitive dependencies like webpack , babal , rxjs , ESLint , etc., to build and run a React project.