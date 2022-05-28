
# AlgoDsGo! - Search, simplified.
This is my first Node.js project, in which I created a search engine that works on codechef and codeforces problems and returns the most relevant results when a query is entered. This project was created from the scratch, with no existing modules or APIs used in the search algorithm.


## Quick Setup Guide (locally)
### Most Important! 
I am using node module natural@2.4.5 for stemming and removing stopwords. Newer versions of it aren't working. So, install version 2.4.5 of natural.

Follow these steps to set up locally:

1) Download the files from the repository.
2) Installing node packages - Open a command prompt window and navigate to the project folder. Type the following commands:

````node
$ npm i express ejs natural@2.4.5 
````
3) File named precomputation.js can use memory which may not be handled by the default node.js allocated memory. Simply run the following command in terminal to fix it:

````node
$ export NODE_OPTIONS="--max-old-space-size=8192"
````

4) Such memory issue won't be there if only index.js is being run. 
5) Run index.js file to host app locally:
````node
$ npm start index.js
````
6) That's it! Locally, the app is ready to go🚀

## Deployed App

https://algodsgo.herokuapp.com/

