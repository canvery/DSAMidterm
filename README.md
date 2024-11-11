# React JS

## What is React JS?

React JS is a popular open source JavaScript library developed by Facebook, mainly used to create user interfaces, especially for single page applications. Its main purpose is to efficiently render user interface components and update them in response to data changes, making the development process smoother for complex and interactive web applications.

### Key features of React JS include:

1. **Component-Based Architecture**: React breaks down the user interface into reusable components, each encapsulating its own logic and layout, making it easier to develop and maintain complex applications.
2. **Virtual DOM**: React uses a virtual representation of the real DOM (Document Object Model) to optimize updates and minimize direct manipulation of the browser's DOM. This results in faster rendering and improved performance.
3. **Declarative Programming**: React allows developers to describe how the user interface should look at any given time. When data changes, React updates and renders components efficiently.
4. **Unidirectional Data Flow**: React follows a unidirectional flow of data, making it easier to track data changes, facilitating debugging and providing predictable behavior.
5. **JSX Syntax**: React uses a syntax extension called [JSX](https://developer.mozilla.org/en-US/docs/Web/XML/Parsing_and_serializing_XML) [(JavaScript XML)](https://developer.mozilla.org/en-US/docs/Web/XML/Parsing_and_serializing_XML) that allows developers to write HTML-like code directly in JavaScript. This makes the code more readable and easier to understand.

## How to install React JS on Windows?

### Step 1: Install Node.js

Start by installing the Node.js installer for Windows. [Click here](https://nodejs.org/en) to visit the official Node.js website and download the LTS version (recommended). Once the installer is downloaded, run it and follow the instructions, making sure not to change the default settings. Click *"Next"* until the installation is complete.


### Step 2: Verify the installation

To ensure that Node.js is installed successfully, open the command line and type:

**node -v**


### Step 3: Install Create React App

Next, type the following command into the terminal:

**npm install -g create-react-app**

The Create React App tool will be installed globally with this command. In order to confirm the installation, type:

**create-react-app –version**


### Step 4: Create a new folder for your react app

Type the following to create a new folder for your React application:

**mkdir newfolder**

Change "newfolder" to the folder name you choose. Enter the folder by using:

**cd newfolder**


### Step 5: Create a New React App

Run the following command within the newly created folder:

**create-react-app your_app_name**

*This will take some time as the necessary dependencies will be installed. Note: Due to npm naming restrictions, the app name must contain only lowercase letters.*


### Step 6: Open Your Project in an IDE

Open your preferred IDE (eg Visual Studio Code) and navigate to the folder where your React app is installed. Enter the directory using:

**cd your_app_name**


### Step 7: Start Your App

Use the following command to launch your application:

**npm start**