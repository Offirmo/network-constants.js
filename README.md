network-constants.js
====================

[![Build Status](https://travis-ci.org/Offirmo/network-constants.js.png?branch=master)](https://travis-ci.org/Offirmo/network-constants.js)
[![NPM version](https://badge.fury.io/js/network-constants.png)](http://badge.fury.io/js/network-constants)
[![Bower version](https://badge.fury.io/bo/network-constants.js.png)](http://badge.fury.io/bo/network-constants.js)
[![status](https://sourcegraph.com/api/repos/github.com/Offirmo/network-constants.js/badges/status.png)](https://sourcegraph.com/github.com/Offirmo/network-constants.js)
[![Total views](https://sourcegraph.com/api/repos/github.com/Offirmo/network-constants.js/counters/views.png)](https://sourcegraph.com/github.com/Offirmo/network-constants.js)

Introduction
------------

Just a bunch of network (only HTTP for now) constants for js programs.

Useful when developing network programs or if you want to use HTTP semantics.

Works in node.js + browser, AMD.

Full testsuite. No dependencies.

Fell free to suggest and contribute.


Usage
-----

```javascript
define(
[
	'network-constants/http'
],
function(http_constants) {
	"use strict";

	console.log( http_constants.methods.get ); // "GET"
	console.log( http_constants.status_codes.status_400_client_error_bad_request ); // 400
	console.log( http_constants.status_messages[404] ); // "Not Found"
	...
```

Installation
------------

Bower : `bower install network-constants.js`
Npm : `npm install network-constants`

Unit tests
----------

in the 'spec' folder. See also readme.txt in the 'test_runner' folder.
