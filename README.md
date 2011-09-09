# ECMA5 Multi-Purpose Javascript Toolkit

## Goals & Features
The JS Toolkit has very specific goals - as to not re-invent the wheel. They go as follows:

* Complete Unit-Test coverage.
* Designed entirely for ECMA5 applications - Node.JS/V8 specifically.
* Performance is key and is achieved through elegance and simplicity.
* ECMA5 introduced a number of new Object definition descriptors which must be respected.
* Eases development by extending type prototypes safely. Object.prototype is left untouched.
* Use accelerated native functions and fully embrace the new ECMA5 specification.

## Installation
It is recommended that you install toolkit globally. It's designed to be a totally generic turbo-charger for javascript's native objects and will hopefully continue to expand and flourish.

> Note if you plan to use it *ensure you include it as an npm dependency* specifying the major version version range. See the versioning section below.

    npm install -g toolkit
    
You can also install it locally into the node_modules folder of the current directory by using the following command:

    npm install toolkit

## Versioning
Versioning is kept simple and is important to note if you choose to include toolkit as a dependency within your application. The version tags follow the following simple-yet-common format: [Major].[Minor].[Revision]

Changes in *Major* versions will likely bring a change to the existing API in other versions.
Changes in *Minor* versions will include new features and bug fixes but should not break your existing API for that major version.
Changes in *Revision* are minor code refactoring/document editing and should largely be ignored.

All new version won't be released until all unit tests pass successfully.

## License
(The MIT License)

Copyright (c) 2011 Oliver Morgan <oliver.morgan@kohark.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.