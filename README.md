# **New-Node-Steps**

### **Creating a new node project:**

1. mkdir a folder for your node project in terminal
2. cd into folder
3. initialize NPM inside project folder with "npm init -y"
4. enter "code ." in terminal to open project in vscode
5. look at data in package.json to confirm that value of "index.js" is present. this is you entry point for running project.
6. touch "index.js" in terminal within node project file to create entry point
7. enter "node index.js" into command line of terminal to run
---

### **Creating and exporting a module:**

1. create JS file such as "myModule.js" containing function that you'd like to export
2. format function as such "module.exports.'~functionName~' = () => 'function'
---

### **Importing and calling module:**

1. import module you have made
    * import module with "const myModule = require('~filepath~')"
    * call function in module with name of JS file in format like so "myModule.'~functionName~'()
    * enter "node index.js" in terminal to run
2. use built in module
    * import module with "const myModule = require('~builtInFunctionName~') *function name usually abbreviated like file system = fs*
    * use same steps as above for importing your own module
3. import node package from third party
    * search for package you would like to install on http://www.npmjs.com and follow instructions on how to install
    * once installed, follow documentation on web page to run module
