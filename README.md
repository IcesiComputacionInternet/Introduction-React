# Introduction-React
Introduction to react


# Frist Steps

For this guide we will be using VS code as IDE.

Download node if you havent: https://nodejs.org/es/download you can get the LTS or the latest version.

Install Prettier in VS code, to format the code https://prettier.io/ (Optional)

Instead of using Create react app, we will be using Vite.

## Create the react app

- In the terminal (mac) or poweshell (windows) run "npm create vite@latest". Be sure to be on Desktok or Documents.
- Accept the download (Y)
- Give the porject a name. (my_react_app)
- Select react
- Select typescript

## Run the app

- Go to the folder of the react app
- Open the terminal or console
- Run "npm install" to install the external dependencies.
- Run "npm run dev" to start the dev server.
- Go to the url that the command provides and check that the app is running.
- Stop the server

## VS code

- Open VS code and open the project folder.
- Setup the VS code terminal
- Run "npm run dev"
- Check that the app is running

# Creating modules

Structure of the project.

<img width="355" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/cbda3259-543a-4edd-bc22-d8fbccfaa4fe">

In the node modules we will find the necesary modules for the project to run. Be sure not to upload this folder to a repo.
In the public folder you'll find the public assets that the apps needs, like public images, logos and others.
In the src folder you'll find the source code of the application. Here will strcuture the diferent modules that we will be creating. The basic module is called App.tsx this is our initial module.

Outside of the folder you'll find the index.html which is the base template of the application. Inside this file you'll find a '&lt;div>' with an id root. This root is where all the components are going to be inserted.


## Creating our first module

- Go to the src folder and add a new file called Message.tsx the .tsx extension is used to note react modules.

- Put inside the following code:
  
<img width="807" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/f94eb7e0-3d2c-4711-a314-5a84218f5ea4">
  
- Go to https://babeljs.io/ and put '&lt;h1> Hello World &lt;/h1> and check the javascript generated code.
  
## Using our module

- Go to the App.tsx and delete all the content.

<img width="483" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/69f6316b-54b4-4ef4-a64b-ec3f0582f4ee">

- Run the app with 'npm run dev' and check the changes.
  
## Add Bootstrapt
  
 To level up the components we will use bootstrap as our css provider.
 - Go to the terminal and run 'npn install boostrapt@5.2.3'
 - Go to main.tsx and replace the import of css with the "import 'bootstrap/dist/css/bootstrap.css'"
  
  <img width="577" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/e795f809-35e6-42b5-8c92-7cfbb7203ec6">

 - Edit Message.tsx with the following code
  
  <img width="841" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/fd7f2dc6-5df5-4cb0-9553-8ccac01504f3">

 - Check the changes and see how we can add classNames to add bootstrap clases and make our clase use CSS
