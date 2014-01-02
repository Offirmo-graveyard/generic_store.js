generic_store.js
================

Introduction
------------

In you web app, you use the convenient local storage instead of fat cookies. Of course,
you use store.js (https://github.com/marcuswestin/store.js) to access the local storage.

Now there are two problems :
- it's hard to unit test you app since local storage is persistent and shared
-


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
