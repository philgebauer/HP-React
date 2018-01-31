# React 
First HP meeting - _1 / 23 / 18_

### Quick Intro

* JavaScript library for building user interfaces.
* A large object / API
* Model–view–controller (MVC) 
    * React is simply the V (View)

### Tools

* Create-React-App
   * Babel, Webpack, JSX formatting 
* Node
* Terminal / Command line 
   * Mac - terminal -> hypr term, bash
   * Windows - cmndr , git bash
* Npm / Yarn
* Git
* Atom, Sublime Text, VS Code
* Homebrew

### ES6
###### [Examples pulled from here!!](https://medium.com/the-react-native-log/a-brief-overview-of-es6-for-react-native-developers-15e7c68315da)

#### Variables 
-----
Var vs Let vs Const

>let: Very similar to var but the scoping is different. var is function scoped (available and can be modified anywhere within a function) whereas let is block scoped, meaning it's available only within that block of code. I pretty much always use let in place of var now (honestly I can't remember the last time I used var).

>const: Same scoping (block) as let but you can't change the value of it, for example:

```
const name = 'Spencer';
name = 'Johnny' // Can't do this
```

BUT - this example is valid -> 

```
const info = {
  name: 'Spencer',
  company: 'Handlebar Labs',
};
info.job = 'Teaching'; // This is perfectly valid
const roles = ['Student', 'Teacher'];
roles.push('Developer'); // Good to go!
```

#### Arrow Functions

**OLD**

```
function funcName(params) {
   return params + 2;
 }
funcName(2);
// 4
```

**NEW**

```
const funcName = (params) => params + 2
funcName(2);
// 4
```

NOTES: 
1. No arguments = parenthesis required
```
const greet = () => {
  return 'Hi!';
};
```

2. One argument = parenthesis optional

```
const greet = (name) => {
  return 'Hello, ' + name + '!';
};
```

3.Two or more arguments = parenthesis required

```
const greet = (name, company) => {
  return 'Hello, ' + name + '!' + 'How is ' + company + '?';
};
```

### Surviving Git / Terminal

**Terminal Cheat Sheet**

Switch directories by using `cd`

View current folder `ls`

Head back to `user` using `cd ~`

Create a file `touch index.html`

Create a folder `mkdir HP-React`

Clear your screen  `cmd + k`

**Git Cheat Sheet**

Creating a new repo - 

Head to github and hit the plus -> `create new repo`

Name your repo

Find and initialize the repo `git init` in terminal

Stage your files `git add .`

Commit them with a message `git commit -m "first commit"`

Point to your github repo `git remote add origin https://github.com/philgebauer/test.git`

Push your files to the online repo (and set the upsteam) `git push -u origin master`

______

Branching in Git

* Allows us to work on the same project, without overlapping code
* Keeps a master/prod branch safe
* Safe testing of new features 




### Homework

Create a Github account, create a couple test repos, and play around with different termainal commands

### Links
http://www.react.express/
https://courses.wesbos.com/account

