# assignment-4-kubal-s
The goal of this assignment is to learn about CSS positioning, Grid layout, SCSS features like variables, mixins, inheritance, loops, functions, math operations, etc.
This project tries to simulate the given page look and feel using SCSS features mentioned above including pure tag and class selectors,combinators,pseudo classes and pseudo elements.

Name: Shalvi Ulhas Kubal
NUID: 001027262

This project is created using HTML and SCSS.

.gitignore was was created using 
1. touch .gitignore
and edited using
2. vim  .gitignore 
press esc and then press I to type and :wq! enter to save the written files to be ignored or :q! to quit directly without saving changes to the .gitignore file 

SASS usage
1. If you have current version please install long term version support of node using nvm
2. Do npm init in folder structure, which will create package.json file
3. Download the nvm install script via cURL:
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.0/install.sh | bash
4. Install the latest LTS version with 
nvm install --lts
5. nvm use --lts
6. Include following in package.json. It will use the main.scss file abd create main.css in specified folder path.
The --watch ensures to recreate main.css if any changes are encountered in main.scss or files imported in main.scss
"scripts": {
    "sasst": "node-sass --watch ./src/assets/scss/main.scss ./src/assets/dist/main.css"
  },


SETUP
1. Download the project/ git clone https://github.com/neu-mis-info6150-spring-2020/assignment-4-kubal-s.git
2. run npm install -g http-server command if http-server not installed


TEST
test the program by running http-server . in the source code folder

and hit localhost:port

where port is where the http-server was started 


