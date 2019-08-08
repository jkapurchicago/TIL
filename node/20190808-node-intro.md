# August 8, 2019 - LEARNING NODE.JS AND NPM  
1. Npm init - Generates a package.json file 
1. Npm install express - Install a package locally 
1. Npm install -g nodemon Install a package globally 
__

* Install 3rd Party Packages(frameworks, libraries, tools, etc.) 
* Packages get stored in the “node_modules” folder 
* All dependencies are listed in a “package.json” file 
* Npm scripts can be created to run certain tasks such as run a server. 

* Node Core Modules (path, fs, http. Etc) 
* 3rd Party Modules/packages install via NPM 
* Custom modules (files) 

```bash
Const path = require(‘path’); 
Const myFile = require(‘./myFile’); 
```

## NODE.JS
`Non Blocking I/O. Works on a single thread using non-blocking I/O c
  Supports tens of thousands concurrent connections ` 
* Optimizes scalability in web applications with many I/o operations.  
* This makes Node.Js extremely fast and efficient 

## Node Package Manager 

1. Install 3rd Party Packages (frameworks, libraries, tools, etc)
2. Package gets installed in the "node - modules" folder 

3. All dependencies are listed in a "Package.Json" file 
NPM scripts can be created to run certain tasks such as run on a server

## COMMANDS ON TERMINAL 
```bash
Last login: Wed Aug  7 13:09:37 on ttys000
Jiamaos-MacBook-Pro:~ Jatin$ node --version #command to check node version  
v10.16.1
Jiamaos-MacBook-Pro:~ Jatin$ npm --version #command to check npm 
6.9.0
Jiamaos-MacBook-Pro:~ Jatin$ node
> 1+1 #you can run javascript on the terminal due to node
2
> const name = 'Brad'
undefined
> console.log('name')
name
undefined
> console.log(name);
Brad
undefined
> name
'Brad'
> function hello() {return 'Hello' + name }
undefined
> hello()
'HelloBrad'
>
(To exit, press ^C again or type .exit)
>
Jiamaos-MacBook-Pro:~ Jatin$
```

```javascript 
function doll(name1) { 
console.log(name1); 
}

//doll('jatin'); 

//GLOBAL objects 
console.log(window); 

setTimeout() //
clearTimeout(); //call a function after a delay

setInterval()  // repeatedly call a function after a given delay 
clearInterval(); // stop a function from being called repeatedly 

window.console.log
window.setTimeout(() => {
    
}, timeout);
```


#PRO TIP - when working in VIsual studio code 

`Make sure vim as an extension is not enabeled, when you try to copy code you will leve insert mode and enter into overtype mode.  ` 

1. Short Cut: Shift + I keaves overtype mode
1. Short Cut Command + Shift + P in VS studio code will bring up the path search bar as well as the run command search bar. 

---
# TO BE CONTINUED... Finishing up Node.Js. Will be adding the project created to test node on GITHUB 
---