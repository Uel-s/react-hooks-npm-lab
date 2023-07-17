# How to create a package.json in my directory

1. Change dir to the folder i wish to add package.json ie cd color-clock.

2. Run npm init.

you will be prompted to confirm the information that will be stored in package.json, starting with the name of the project.

3. Press enter to the end then enter yes to confirm the packages.

 A fully constructed package.json file will then appear in the color-clock directory.


 # Add a Script

 Here i run npm test to view whats in the test file under script

 Scripts are often useful for things like testing or to start a necessary process, like a local server.

# Install a Package

With package.json set up, we can now add a package we want to include in our project.

I want to include a package called date-fns to my dir color-clock

1. First we run npm install date-fns

This command will add the package to the list of dependencies in package.json.

2. npm install serve

   Used to run our app in the browser

3. npm start 

"scripts": {
  "test": "echo 'Hello World!'",
  "start": "serve"
}

 add the start:serve to show network

4. Copy paste the url to browser. 

The clock wont work be shown if we run the address in my browser since because  not all of the files in our project are currently set up.

5. Press ctrl + c to stop server from running.

6. install  esbuild by running $ npm install esbuild.

esbuild is a js bundler which is a tool that handles all of a project's
dependencies, and combines the code into a single file that is browser-ready

7. run $ npm run build

8. in html  Change the src property to `dist/out.js`.
 <script src="/color-clock/dist/out.js" type="module"></script>



