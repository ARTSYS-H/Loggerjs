<div align="center">

# @artsys/loggerjs

![npm (scoped)](https://img.shields.io/npm/v/@artsys/loggerjs?color=critical&logo=npm)
![NPM](https://img.shields.io/npm/l/@artsys/loggerjs)

[![GitHub stars](https://img.shields.io/github/stars/ARTSYS-H/loggerjs?logo=github)](https://github.com/ARTSYS-H/loggerjs/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ARTSYS-H/loggerjs?logo=github)](https://github.com/ARTSYS-H/loggerjs/network)
<!--[![GitHub license](https://img.shields.io/github/license/ARTSYS-H/loggerjs)](https://github.com/ARTSYS-H/loggerjs)-->

**Add an easy and aesthetically pleasing console logging for your project.**


</div>


## Installation

You can use the following command to install this package.

```sh
$ npm install @artsys/loggerjs
```

## Usage

```js
const logger = require("@artsys/loggerjs");

logger.log("Here is your log", "log");
logger.log("Here is your log");
// => [2022-02-09 10:08:36]: LOG Here is your log

// OR
logger.log("Here is your log", "error");
logger.error("Here is your log")
// => [2022-02-09 10:09:26]: ERROR Here is your log
```

|   available types   |   available types   |
| :-----------------: | :-----------------: |
|         log         |         gray        |
|         warn        |        yellow       |
|         error       |         red         |
|         debug       |        magenta      |
|         cmd         |         white       |
|         ready       |         green       |
