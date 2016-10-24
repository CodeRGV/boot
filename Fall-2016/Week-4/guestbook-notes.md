# Skills

* list installed npm packages, local and global
* uninstall npm packages, local and global
* review and edit package.json to install specific versions of dependencies for tutorials
* current version of express-generator
* launch mongo server and connect mongo interactive shell
* use mongo shell to create objects, query/find, update, delete

Assignment: https://github.com/CodeRGV/boot/blob/master/Fall-2016/Week-4/Guestbook.md

## Resource: DreamersLab tutorial (todo list)

* uses mongoose and schema for mongo connection
* uses ejs for templating

## Resource: Dead-simple step-by-step guide (User)

* uses monk for mongo connection
* uses jade for templating

## Resource: (optional, on your own): Heroku, example of restful interface


## Notes for Dead Simple

### Part I - 15 minutes of installing

The tutorial refers to C:\node. On the Mac, we will use the boot directory. PC users should be continuing with the directory they've set up for projects.

* Step 1: Node is already installed, verify version with node --version
* Step 2: Verify installed version of express-generator
* Step 3: Create an Express project.
* Step 4: Be sure to follow the version information in the package.json file
* Step 5: Install dependencies. For mongo on Mac, start the service with brew services start mongo. Where is my data folder on Mac? db.serverCmdLineOpts()

### Part II - Hello, World!

helloworld.jade

### Part III - MongoDB

* Step 1: Mongo may already be installed.
* Step 2: For mongo on Mac, start the service with brew services start mongo. For PC, refer to your notes or confirmWhere is my data folder on Mac? db.serverCmdLineOpts()
* Step 3: Create a database. In the Mongo console
* Step 4: The first "look like this" example is not entered, just to display an example
* Step 5: Hook up Mongo
* Step 6: Pull data
  *Do not try to fix the error " Error: Cannot find module '../build/Release/bson' "

### Part IV - Writing to the DB

* Step 1: Create your data input
* Step 2: Create your DB functions
