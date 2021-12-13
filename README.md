Project description:

In this project we well developing a web base system for food text classification.

Features:
We add some features in index.html file, we edit the UI landscape.

Issue:
we have some issue in travis ci all build was run and the problem was because package.json, we change:
 "scripts": {
  "test": "echo \"Error: no test specified\" && exit 1"
},  
To:
"scripts": {
  "test": "echo \"No test specified\""
}, 
