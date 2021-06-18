# Express init app

listens at port `3000`

<br>

| Express  |  EJS Templating  | Node.js |
|------------------------|:---------------------------------| ---------|
| [Guide](https://expressjs.com/en/guide/routing.html) | [Documentation](https://ejs.co/#docs)  | [Introduction](https://nodejs.dev/learn) |
| [Getting started](https://expressjs.com/en/starter/installing.html)| [Getting Started](https://ejs.co/#install) | [Getting Started](https://nodejs.org/en/docs/guides/getting-started-guide/) |
| [Glossary](https://expressjs.com/en/resources/glossary.html) | [ejs](https://www.npmjs.com/package/ejs) npm | [16.3.0 Documentation](https://nodejs.org/api/all.html)|
| [express](https://www.npmjs.com/package/express) npm | [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-use-ejs-to-template-your-node-application) Templating guide | [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-write-and-run-your-first-program-in-node-js) Guide   |
<!-- | | | -->
<!-- | | | -->

<br>

## Node.js

<br>

[Node.js Installation](https://nodejs.org/en/download/)

<br>

If you get node's version with `node -v` install some packages globally

`npm install express npx express-generator -g`

<br>

## Express new project

 `myapp` indicates the folder that `npx` will generate the project , folders and files can be renamed as accordingly

`express -v ejs myapp`

- [express-generator](https://www.npmjs.com/package/express-generator) npm 
- [npx](https://www.npmjs.com/package/npx) npm

<br>

## npm packages

`npm install -D nodemon` install nodemon as a developer's dependency and change `package.json` run scripts to include `nodemon` in start command as well


mysql2 is needed for CRUD `npm install mysql2`

- [nodemon](https://www.npmjs.com/package/nodemon) npm
- [mysql2](https://www.npmjs.com/package/mysql2) npm

<br>

<!-- 
|  tables  |      aree     | coool |
|----------|:-------------:|------:|
|   col 1  |     col 1     |   $   |
|   col 2  |     col 2     |   $   |
|   col 3  |     col 3     |   $   | -->


## npm package manager

<br>

[npm Docs](https://docs.npmjs.com/)

<br>

`npm -v` to get the version

`npm help` to cat help

`npm init --yes` `-y` to initialize a new project 

`npm run script` in order to run a script listed in your `package.json`

`npm root -g` global modules path

<br>

#### Managing packages

`npm install package` `-i` `-g` install as dependency

`npm install package@4.17.3` `-i` `-g` install a particular package version

`npm install package --save-dev` `-D`   /// installs as developers dependency

`npm remove package` `-r` `-g` removes installed package	

`npm list` `-g` lists all packages 
`npm list --depth 0` , 
`npm list --depth 1`

##### other packages

`sudo npm install n -g` n version manager

`sudo npm install live-server`

`sudo npm install nodemon`

`sudo npm install express`

##### Finding packages

`npm search package` to look for a package

`npm view package` details of a package  

#### Update packages

`npm update package` to update a particular package

`npm update` to update all local packages 

`^ major 4.x.x` , `~ minor 4.4.x`

##### `npm` update

`sudo npm install npm@latest -g` for latest `npm version

<br>

#### Configuration

[npm config](https://docs.npmjs.com/cli/v7/using-npm/config)

`cat package.json` lists package configuration

`npm config ls -l` configuration list

`npm config get prefix`	local prefix 

`npm config set prefix /Users/dev/path`  to change local prefix path

##### Set

`npm config set init-author-name "YOUR NAME"`

`npm set init-license "MIT"`

##### Get

`npm config get init-author-name`

`npm get init-license`

##### Remove

`npm config delete init-author-name`

`npm delete init-license`

<br>

`npm cache clean --force`	npm manages cache but itself but if needed you can force a clean

<br>


