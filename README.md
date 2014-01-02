network-constants.js
====================

[![Build Status](https://travis-ci.org/Offirmo/network-constants.js.png?branch=master)](https://travis-ci.org/Offirmo/network-constants.js)

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


Unit tests
----------

in the 'spec' folder. See also readme.txt in the 'test_runner' folder.
