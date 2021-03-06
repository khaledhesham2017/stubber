<h1 align="center">Welcome to stubber 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/@mohamed-abdelrhman/stubber" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/@mohamed-abdelrhman/stubber.svg">
  </a>
  <a href="https://github.com/mohamed-abdelrhman/stubber#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/mohamed-abdelrhman/stubber/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/mohamed-abdelrhman/stubber/blob/master/README.md#-license" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/npm/l/@mohamed-abdelrhman/stubber?style=flat-square" />
  </a>

</p>

> small package alternative for nestjs cli that creates a module files for you for those who use different project architecture different from the standard one introduced by nestjs hence can't use its cli.


## Install

```sh
npm i @mohamed-abdelrhman/stubber
```

## Usage
create all module files:
```sh
stubber -g module-name -A
```
create all basic module files:
```sh
stubber -g module-name -B
```
create new input file for graphql:
```sh
stubber -g module-name -i input-name
```
create all type file for graphql response :
```sh
stubber -g module-name -t type-name
``` 
### What files does stubber generates
it creates all the below files and the imports between them
```sh
module-name.module.ts
module-name.service.ts
module-name.repository.ts
module-name.resolver.ts
module-name.resolver.ts
entities/module-name.entitiy.ts
types/type-name.type.ts
inputs/input-name.input.ts
``` 

## Todo List
<li>Create command for each possible file that might be created by the user</li>
<li>Option for basic crude operations with the files generation</li>
<li>Support different native connections and different ORMs rather than typeorm like mongoose and sequelize</li>
<li>Support different project architectures and patterns  like CQRS</li>

## Author

👤 **Mohamed Abdelrhman <mohamed95abdelrhman@gmail.com>**

* Github: [@mohamed-abdelrhman](https://github.com/mohamed-abdelrhman)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/mohamed-abdelrhman/stubber/issues). You can also take a look at the [contributing guide](https://github.com/mohamed-abdelrhman/stubber/blob/master/CONTRIBUTING.md).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2021
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
