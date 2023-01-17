## Chapter-01

#### What is Emmet
Emmet uses different abbreviations and short expressions depending on what's passed, and then dynamically converts the abbreviations into the full code, example as
` div.wrapper —> <div class="wrapper"></div>` 
` h1.header.center —> <h1 class="header center"></h1> `

=============
#### Difference between a Library and Framework
 A framework provides everything to build an application including routing, apis, different rendering mechanism etc. It can be called that Framework is a superset of libraries, whereas a library can be a set of helper functions, modules for specific functionality.
 
=============
 #### What is CDN? Why do we use it?
 A CDN (content delivery network), also called a content distribution network, is a group of geographically distributed and interconnected servers. They provide cached internet content from a network location closest to a user to speed up its delivery.

#### Why is React known as React?
The name "React" was chosen because the library was designed to allow developers to "react" to changes in state and data within an application, and to update the user interface in a declarative and efficient manner.

####What is crossorigin in script tag
CORS is used to manage cross-origin requests.
CORS stands for Cross-Origin Resource Sharing, and is a mechanism that allows resources on a web page to be requested from another domain outside their own domain. It defines a way of how a browser and server can interact to determine whether it is safe to allow the cross-origin request. CORS allows servers to specify who can access the assets on the server, among many other things.

#### What is diference between React and ReactDOM
These are two different package which works together to render the html elements in the webpage. React package contains: React.createElement, React.createClass, React.Component, React.PropTypes, React.Children. On the other hand React DOM's responsibility is to render the react element/components to the dom. React DOM's equivalents are React native, React-three etc for different platforms which is only used once in index.html file to render the root element

#### What is difference between react.development.js and react.production.js files via CDN?
react.development.js is used for the develeopment purpose which dosn't have the minified version of javascipt codes, whereas react.production.js is the minified version and it is more optimized which is the reason it is used in production environment.

#### What is async and defer
For async attribute: The js code downloaded while HTML parsing and gets executed, whenever it gets downloaded fully. Thus it does not guarentee the order of the execution 2. For defere attribute: The js code gets downloaded while HTML parsing. And only after the HTML parsing is completed the js file gets executed, thus it guarentees the order of the execution