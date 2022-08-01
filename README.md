# tic-tac-toe

This is an interactive tic-tac-toe game with React. The instructions below are for setting up on local machine.
To make online domo available, I load React library online in "index.html" and comment "import React" code in "index.js".


### Make sure you have a recent version of Node.js installed.
Follow the installation instructions for Create React App to make a new project.

npx create-react-app my-app

### Delete all files in the src/ folder of the new project
Note: Don’t delete the entire src folder, just the original source files inside it. We’ll replace the default source files with examples for this project in the next step.

cd my-app
cd src

If you're using a Mac or Linux:
rm -f *

Or, if you're on Windows:
del *

### Then, switch back to the project folder
cd ..

Add a file named index.css in the src/ folder with this CSS code.

Add a file named index.js in the src/ folder with this JS code.

Add these three lines to the top of index.js in the src/ folder:
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';

Now if you run 
npm start 
in the project folder 
and open http://localhost:3000 in the browser, 
you should see an empty tic-tac-toe field.
