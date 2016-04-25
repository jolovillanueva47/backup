Javascript Notes
======

04/25/2016
----------

"===" vs "=="

The 3 equal signs mean "equality without type coercion"

0 == false   // true

0 === false  // false, because they are of a different type

1 == "1"     // true, automatic type conversion for value only

1 === "1"    // false, because they are of a different type

null == undefined // true

null === undefined // false

'0' == false // true

'0' === false // false

Javascript has some comparison with Scala in some built in functions.
higher order function are use for composability or elegance in coding
Functions also in Scala:
	1.filter
	2.map
	3.reduce
In higher order functions, **functions are values**