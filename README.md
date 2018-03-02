[//]: #@corifeus-header

 [![Build Status](https://travis-ci.org/patrikx3/corifeus-utils.svg?branch=master)](https://travis-ci.org/patrikx3/corifeus-utils)  [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/patrikx3/corifeus-utils/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/patrikx3/corifeus-utils/?branch=master)  [![Code Coverage](https://scrutinizer-ci.com/g/patrikx3/corifeus-utils/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/patrikx3/corifeus-utils/?branch=master)  
 
  
[![NPM](https://nodei.co/npm/corifeus-utils.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/corifeus-utils/)
---
# Corifeus Utils - Memory v1.1.836-291  

This is an open source project. Just code. If you like this code, please add a star in GitHub and you really like, you can donate as well. Thanks you so much!

Given, I have my own server, with dynamic IP address, it could happen that the server for about max 5 minutes can not be reachable for the dynamic DNS or very rarely I backup with Clonzilla the SSD or something with the electricity (too much hoovering or cleaning - but I worked on it, so should not happen again), but for some reason, it is not reachable please hang on for 5-30 minutes and it will be back for sure. 

All my domains (patrikx3.com and corifeus.com) could have errors right now, since I am developing in my free time and you can catch glitches, but usually it is stable (imagine updating everything always, which is weird).

### Node Version Requirement 
``` 
>=8.9.0 
```  
   
### Built on Node 
``` 
v9.7.1
```   
   
The ```async``` and ```await``` keywords are required.

Install NodeJs:    
https://nodejs.org/en/download/package-manager/    



# Description  

                        
[//]: #@corifeus-header:end

Misc utils (async array iterator, random characters, exit on silent ```unhandledRejection``` errors, etc...)

```javascript
const utils = require('corifeus-utils');
```

* Modules
  * Async Array Iterator ```forEachAsync```
  * ```JSON.strintify``` for ```Error```
  * Lodash Pascal
  * Remove silent process ```unhandledRejection``` end ```process.exit()```, adds timestamp
  * Process ```uncaughtException``` that shows timestamp.
  * Random async Base62 string
  * Replace inject - finds a prefix and postfix in a string and replace the content, ```strings.inject```
  * Convert a byte array or string to base62, ```utils.base.charset(string)```
  * Async Hash (SHA-512, SHA-256) file using Base62,
  * Promise based HTTP Request
  * Time utilies
  * Additional file system utils
  * JSON based file database
  * HTTP/HTTPS based async/Promise request
  
# Actual modules
  
* time
  * verbose
  * span
* regexp
  * escape
* random
  * async (default is base62)
  * complexUuid
* promise
  * deferred (simple extract the reject, resolve and promise function, instead of callback)
* process
  * unhandledRejection
  * uncaughtException
  * writableCallbackExit
* object
  * reduce
* hash
  * async file
* string
  * padStart
  * empty
  * inject
* lodash
  * PascalCase
* http
  * async request
* db
  * file based json storage
* child-process
  * async exec
* array
  * forEachAsync, async/await for each

  
[//]: #@corifeus-footer

---

[**CORIFEUS-UTILS**](https://pages.corifeus.com/corifeus-utils) Build v1.1.836-291 

[![Like Corifeus @ Facebook](https://img.shields.io/badge/LIKE-Corifeus-3b5998.svg)](https://www.facebook.com/corifeus.software) [![Donate for Corifeus / P3X](https://img.shields.io/badge/Donate-Corifeus-003087.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QZVM4V6HVZJW6)  [![Contact Corifeus / P3X](https://img.shields.io/badge/Contact-P3X-ff9900.svg)](https://www.patrikx3.com/en/front/contact) 


## Sponsor

[![JetBrains](https://www.patrikx3.com/images/jetbrains-logo.svg)](https://www.jetbrains.com/)
  
 

[//]: #@corifeus-footer:end
