This repository has  **basic** settings for building React application.  
It is designed for self use and probably gonna grow with time.
#
Build in settings:
- React / ReactDOM
- Parcel Bundler
- Jest (with ES6 Syntax tolerance)
- Redux (with connect-component example)
- separated ./src/components directory

+ no css framework   

# 
Entry point:
- ./src/index.html
- Start development in ./src/components/App/App.jsx

# 
TODO:
+ add webpack 

#
Quick start:  

Clone the git repo:  
`git clone https://github.com/Sazar24/react-starter name_of_new_project`  
`cd name_of_new_project`  
Run `npm i` to install dependencies.  
`npm start` to run server at localhost.  
`npm test` or `jest --watch` to run test.  
  
#
Saving changes:  

To push commits to another repo, firstly run:  
`git remote set-url origin http://github.com/YOU/YOUR_REPO`
now you cant run `git push` .

#

Removing commits history (simple, but brutal - and **not perfect**! - way):  

-- Remove the history from repo - locally:   

`rm -rf .git`  

-- recreate the repo from the current content only 

`git init`  
`git add .`  
`git commit -m "Initial commit"`  
  
-- push to the github remote repo ensuring you overwrite history  

`git remote add origin git@github.com:<YOUR ACCOUNT>/<YOUR REPOS>.git`  
`git push -u origin master`  