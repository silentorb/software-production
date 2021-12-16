# Tech Startup Web Stack

## Common

### Node.js

#### Pros

* Same language across frontend and backend
* Same core stack across frontend and backend
* Using a scripting language lends itself to rapid development and a low barrier to entry for developers
* One of the most extensive and modular software ecosystems in existence
* Within the tech startup domain, Node.js is the most common stack foundation and the easiest base to find developers for

#### Cons

* Scripting-style module system
  * Needless distinction between local and third-party modules, making it difficult to partion local code into modules and to maintain third-party modules
  * At it's heart, Node.js imports are simply executing imported script files, with no real separation between module metadata from executable code
    * This creates unneccesary importing performance challenges
    * The pattern of using an index.js file as the root of a directory or module is a hack that dynamically populates a module object with every member of that module
      * This can lead to unexpected and obscure bugs due to importing appearing to be atomic when it isn't
      * With a more robust module system, index.js files would not be needed
  * It can be challenging to maintain disciplined boundaries between modules because it is valid Node.js code to relatively import a module
    * This is most often faced when using IDE tools to move code around, where it is ambiguous how moved dependents or dependencies should handle referencing and the IDE has to make its best guess and sometimes guesses wrong
* Weak typed
  * While the V2 engine jumps through amazing hoops to optimize JavaScript code, strong typing allows for simpler and more efficient optimizations
  * While injecting strong typing via [TypeScript is recommended](#TypeScript), the technicalities and UX of injecting strong typing is not nearly as clean and seamless compared to a runtime with built-in strong typing
* 

#### Kotlin JVM

* As a business grows, Kotlin JVM is a good later option for robust, high-performance web services
  * Kotlin JVM has none of the listed cons of Node.js
  * Kotlin JVM has a steeper learning curve than Node.js and is not used in as many startups

## TypeScript

Benefits