# JSONfn - Nodejs plugin

nodejs plugin to convert **object with functions** to string and string to object.

**Version** - 0.30.0

**Copyright** (c) 2012 Vadim Kiryukhin ( vkiryukhin @ gmail.com )

**Home page:** [http://www.eslinstructor.net/jsonfn/](http://www.eslinstructor.net/jsonfn/) 

**License:** Dual licensed under
the MIT and GPL licenses:

[http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)

[http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html)

##Description

* `JSONfn.stringify(objfn)` - convert object to string; 

* `JSONfn.parse(strfn)` - convert string to object; 

**PARAMETERS:**

`@objfn` - javascript object with (or without) functions; 

`@strfn` - string, which was produced by JSONfn.stringify() function; 
 

**USAGE:**

`var strfn  = require('../jsonfn').JSONfn.stringify(obj);`

`var objfn = require('../jsonfn').JSONfn.parse(strfn);`





