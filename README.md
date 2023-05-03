# MERN LESSONS - BA40FS_MERN


### 24032023-Keywords

1. SPA (React,NodeJS,Angular) vs MPA(.Net, Java, PHP)
2. React
3. React Virtual DOM
4. Component
5. JSX
---

### 25032023-Keywords

01. EcmaScript----ES15
02. Let vs Const (var)
03. Default Parameter
04. Arrow Function =>
05. OOP
06. Spread Operator (...)
07. forEach, Map
08. JSON Data
09. Array Filter - Object Assing
10. https://nodejs.org/en
11. https://code.visualstudio.com/
12. https://desktop.github.com/
13. https://github.com/fdikmen/BA40FS_MERN
14. Extensions; Prettier - Code formatter, Auto Rename Tag, Auto Close Tag, ES7+ React/Redux/React-Native snippets, Live Share
15. npm init ---> package.json
16. npm
17. npx
18. npm vs yarn
19. Hello World with React (https://react.dev/learn/start-a-new-react-project)
npx create-react-app hello-world
20. Folder Structure
21. npm run build - FOR BUILD FOLDER
22. index.js
---

### 26032023-Keywords

 1. Add file to GitHUB
 2.  `npm init -y`
 3. Module System
(Babel, `npm install babel-cli babel-preset-es2015` , `"start":"babel-node main.js --presets es2015"` , import-export-default-as-*)
 4. Component (extends)
 5. Dikkat Edilmesi Gerekenler;
		 1. Live Share de çalışma,
		 2. Komutları İlgili Klasörde Yazmaya Çalış,
		 3. Uygulama Oluşturmak İçin `npx create-react-app [APP-NAME]` komutunu kullan,
		 4. Eğer eklentilerde bozulmalar oluyorsa; `ES7+ React/Redux/React-Native snippets` harici eklentileri
    silebilirsiniz.
---
### 31032023-Keywords
1. props
---
### 01042023-Keywords
1. props
2. React Developer Tools
3. PropTypes
4. Constructor
5. Style
6. Combine styles (Spread & Object.Assing)
7. Events & Bind
8. Get Github Repo
9. send function with props & parameters
---

### 02042023-Keywords

1. Data Bind Methods
a. With Function
b. in Constructor
c. With Arrow Function
2. State
3. re-Render (React Diff - React Virtual DOM)
4. Counter (First App)
5. Class vs Functional Comp. (Stateful vs Stateless)
6. PhoneBook (Second app) --> npx create-react-app phonebook

Component, import-export, classComponent, PropTypes, State, Spread (Array Merge), props (array,function)

React Developer Tools, Array.Filter & Array.indexOf

---

### 07042023-Keywords

1. Summary for Phone Book App

---

### 08042023-Keywords

01. LifeCycle - React LifeCycle
02. React Component LifeCycle
[https://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/]
-- Mounting - Updation - Unmounting
03. I. Constructor (Mounting)
04. II. Render -> PURE
05. III. ComponentDidMount
06. IV. ComponentDidUpdate
07. V. ComponentWillUnmont
08. VI. getDerivedStateFromProps
09. VII. shouldComponentUpdate
10. VIII. getSnapshotBeforeUpdate
11. FETCHING
MOCK ==> https://jsonplaceholder.typicode.com/
---
### 09042023-Keywords
01. Fetch (Summary)
02. Axios
```Node
npm i axios
```
03. Router
```Node
npm i react-router-dom
```
Project Stop => CTRL + C
04. BrowserRouter (wrapping) - Link - Routes | Route (path-element)
MainLink-HomeLink(/) - No Match(*) - Read Parameter - NavLink

---

### 14042023-Keywords

01. Summary
02. Advanced Components - Higher Order Component
---

### 15042023-Keywords

01. Summary
02. Advanced Components - Higher Order Component
03. Redux - npm i redux react-redux

**Sample**
npm i redux react-redux axios
**Means**
npm i redux
npm i react-redux
npm i axios
**SAVE**
npm i [libName] --save
**FORCE**
npm i [libNAME] -f (or --force)

4. UI-View-Comp. => ACTION => dispatch => STORE => REDUCER => subscribe => UI-View-Comp.
5. createStore , reducer(like function), .getState() , dispatch
6. npm i @reduxjs/toolkit
- SUGGEST
Intellisense -> Suggest
Snippet -> ShortCut
---

### 16042023-Keywords

**Folder Structure**
https://medium.com/@fdikmen/a-redux-toolkit-project-structure-guide-58093baa88a5

**Home Work**
https://github.com/fdikmen/BA40FS_MERN/blob/main/Lesson12/HomeWork.md


- redux-toolkit RTK
- Folder structure
- Slice (IntialState - Name - Reducer - Aciton)
- Store
- Provider
- useDispatch
- redux devTools Extension
- useSelector
https://redux-toolkit.js.org/introduction/getting-started

#### npx create-react-app [appName] --template redux
```bash
npx create-react-app [appName]
npm i  @redux-toolkit
npm i  react-redux
Create Folder  Structure
Create Sample  Files (Comp., Slice)
Create Store
```
https://jsonplaceholder.typicode.com/users/2

- middleware
- HOOKS
- STATE => useState
- LIFECYCLE => useEffect
 

next suggest => [**Next.JS**]

---
### 28042023-Keywords

01. Summary
02. API - Http Methods (CRUD)
03. mockapi.ai
04. Postman

---
### 03052023-Keywords

01. NPM?
npm i [packageName]  -|- npm install [packageName]
npm i -y --> start file(package.json)

02. import (React) vs require (NodeJS)

03. Global vs Local Package
Global ==> npm i -g [packageName] -|- npm i --global [packageName]
Local  ==> npm i [packageName]

````
npm list -g
npm list -g --depth=0
```

Windows     Console Clear => cls
MacOS/Linux Console Clear => clear

Use global package
```
npm link [package]
```

04. Create a Project with npm
(Create a package.json file)
Manuel
```
npm init
```
Auto
```
npm init -y
```
Settings Sample
```
npm set init.author.name "fdikmen" ===> npm config ls -l
```

05. Install a Module (Lib)

```
npm install [moduleName]
npm i [moduleName]
```

06. License

https://choosealicense.com/licenses/ 

07. npm-cache

- npm i npm-cache
- npm i [packageName] => npm-cahce install [packageName]

08. -s --save --no-save

09. Old Version
Install specific vesion for package
```
npm i [packageName]@[Version] 
```
List outdated packages
```
npm outdated
```
Update packages
```
npm update
```

10. Package for Developer 
````
npm i [packageName] --save-dev
```

11. Define script in package.json file
```
npm run [commandName]
```

12. Install Multiple Package

```
npm i [packageName01] [packageName02] [packageName03] ...
```

13. Remove a Package

```
npm uninstall [packageName]
```


