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

<img width="305" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/f59cfa1e-5f87-4aad-b418-3b214208764c">


In the node modules we will find the necesary modules for the project to run. Be sure not to upload this folder to a repo.
In the public folder you'll find the public assets that the apps needs, like public images, logos and others.
In the src folder you'll find the source code of the application. Here will strcuture the diferent modules that we will be creating. The basic module is called App.tsx this is our initial module.

Outside of the folder you'll find the index.html which is the base template of the application. Inside this file you'll find a '&lt;div>' with an id root. This root is where all the components are going to be inserted.


## Creating our first module

- Go to the src folder and add a new file called Message.tsx the .tsx extension is used to note react modules.

- Put inside the following code:
  
<img width="834" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/99873ad7-13fc-44ad-94bf-9098e014a50c">

  
- Go to https://babeljs.io/ and put '&lt;h1> Hello World &lt;/h1> and check the javascript generated code.
  
## Using our module

- Go to the App.tsx and delete all the content.

<img width="572" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/21a91c65-f60c-400d-9c5c-5e6b00a4b565">

- Run the app with 'npm run dev' and check the changes.
  
## Add Bootstrapt
  
 To level up the components we will use bootstrap as our css provider.
 - Go to the terminal and run 'npn install boostrapt@5.2.3'
 - Go to main.tsx and replace the import of css with the "import 'bootstrap/dist/css/bootstrap.css'"
  
  <img width="562" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/0db9244d-144e-4028-ad45-c0a186b3ea40">


 - Edit Message.tsx with the following code
  
  <img width="856" alt="image" src="https://github.com/IcesiComputacionInternet/Introduction-React/assets/17294264/54ec5c85-7377-4423-80a0-e8a858517dc8">

 - Check the changes and see how we can add classNames to add bootstrap clases and make our clase use CSS
