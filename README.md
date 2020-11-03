# Some React Interview Questions

1. Is React Faster? Yes

2. How many times faster ?
   10 times faster compared to Angular

3. React is Library or framework?
   Library

4. What is framework Vs Library?

rules and regulations is called framework

no rules and regulations is called Library

5. Diff b/w Angular to React?
   Angular will work on Real DOM, React will work on Virtual DOM

6. Is React component based? Yes

7. Is Angular component based? yes

8. because of component code reusability is high

9. react released by facebook

10. Angular released by Google

11. Angular released in which year 2012

12. React released in 2013, famous in market from 2016

13. Who is light weight ? React

14. who follows virtual DOM? React

# React Environmental Setup

============================

1. download and install NodeJS

   - "npm" is the tool, present in Node JS, helps to install ReactJS
   - "npm" stands for node packing manager

   website: https://nodejs.org/en/download/

   File:node-v14.15.0-x64.msi

   -msi stands for microsft installer

2. Install yarn tool

   - yarn tool provided by Facebook.

   - yarn tool, used to download the libraries in faster manner.

   - npm install -g yarn@latest

   - "npm" stands for node packing manager.

   - "-g" stands for global installation.

3. Install "create-react-app"

   - helps to create the react projects.

---

In How many ways we can React Applications? JSX and TSX

How to create the react application.

1. Create the directory
   Ex. class_applications

2. Switch to class-applications

   > cd React-Installation

3. create the react application

   > create-react-app first-app

   - the default port no of react application is 3000

   - "first-app" is the react application.

4. switch to react application.

   > cd first-app

5. execute the react application.

   > yarn start / npm start

# Directory Structure of react application

===============================

1.  node_modules

    - node_modules contains libraries, these libraries helps to execute the application.

2.  public folder

    - All the main files of react application we will keep in public directory.

    - names are fixed and will not change in production environment.

    - these files have cache mechanism.

3.  public/ favicon.ico

    - this is default logo of react.

4.  public / index.html

    - react starts the execution from index.html file

    - index.html contains dom element(div) whose id is "root".

5.  public / logo192.png

          / logo 512.png

    - these logos are helps to execute react application in different resolutions.

6.  public / manifest.json

    - used to configure the mobile application development.

7.  public / robots.txt

    - if helps to write SEO technics.

8.  src folder

    - it is used to deploy components(to keep components).

9.  src / App.js
    / App.css
    / App.test.js

    - App component is the default component.

10. src / index.css

    - it is used to define global styles for component.

11. src / index.js

    - this file is configuration file.

    - this file used to configure components.

12. src / logo.svg --> Solar Vector Graphic

    - by default the logo is rotating because of svg image.

13. src / reportWebVitals.js(PWS --> progressive web app)

    - to configure PWS environment.

    - PWS stands for Progressive Web Apps.

14. src / setupTests.js

    - this file is supporting file to implement unit test cases.

15. src / package.json

    - it is used to download the libraries.

    Questions:

    1. What is location of libraries? node_modules

    2. How to download the libraries? with the help of package.json

    3. where to keep important files? public

    4. what is index.html ? main html file with <div id="root">

    5. who is the default component? App.js

    6. what is configuartion file? index.js

    7. why render ? to execute the component

    8. Why setuptest.js ? used to provide the guidance for writing unit test cases.
