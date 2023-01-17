## Chapter-02

#### What is `NPM`
NPM is an open source repository of different packages that is used to manage packages, develop application and websites

=============
#### What is `Parcel/Webpack`? Why do we need it?
 Parcel and webpack are the bundlers used mostly for JavaScript or Typescript code that helps you to minify, clean, and make your code compact so that it becomes easier to send a request or receive the response from the server when it usually takes you to transfer multiple files without using any bundler for loading the page of your application
 
=============
 #### - What is `.parcel-cache`
 Cache folder (or . parcel-cache in parcel v2) stores information about your project when parcel builds it, so that when it rebuilds, it doesn't have to re-parse and re-analyze everything from scratch. It's a key reason why parcel can be so fast in development mode.

####  What is `npx` ?
which will execute the package without installing it. NPM is used to install packages, which we should do if our project requires dependencies or packages.
The npx stands for Node Package Execute and it comes with the npm, when you installed npm above 5.2.0 version then automatically npx will installed

#### What is difference between `dependencies` vs `devDependencies
A dependency is a library that a project needs to function effectively. DevDependencies are the packages a developer needs during development.

`npm install -D parcel`

#### What is Hot Module Replacement
Hot Module Replacement is a feature that enables you to see code changes in the browser without having to refresh it, allowing you to preserve the state of your front-end application.

####  What is the difference between `package.json` and `package-lock.json`
##### package.json
It contains basic information about the project.
It is mandatory for every project.
It records important metadata about the project.
It contains information such as name, description, author, script, and dependencies.

##### package-lock.json
It describes the exact tree that was generated to allow subsequent installs to have the identical tree.
It is automatically generated for those operations where npm modifies either node_modules tree or package.json.
It allows future devs to install the same dependencies in the project.
It contains the name, dependencies, and locked version of the project.

#### Why should I not modify `package-lock.json`?
This means you can guarantee the dependencies for other developers or prod releases, etc. It also has a mechanism to lock the tree but generally will regenerate if package.json changes.

#### What is `node_modules` ? Is it a good idea to push that on git
The node_modules folder is used to save all downloaded packages from npm in your computer for the JavaScript project that you have. Developers are always recommended to do a fresh install with npm install each time they downloaded a JavaScript project into their computer.
Do not check node_modules into git for libraries and modules intended to be reused. Use npm to manage dependencies in your dev environment, but not in your deployment scripts

#### What is the `dist` folder?
The shortform dist stands for distributable and refers to a directory where files will be stored that can be directly used by others without the need to compile or minify the source code that is being reused.

### What is `browserlists`
Browserslist is a tool that allows specifying which browsers should be supported in your frontend app by specifying "queries" in a config file.
Let's see each individual query in your example:
0.2%: All browsers that have at least 0,2% of global market share
not dead: Exclude browsers without official support in the last 24 months
not ie <= 11: Exclude IE 11 and older versions
not op_mini all: Exclude Opera Mini