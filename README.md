#string.js
A few javascript functions for strings.

##Usage
	var a = "something".startsWith("some");

##Methods
####startsWith
Returns true if a string starts with another string passed as parameter.

	var a = "something";
	a.startsWith("some"); // returns true

####endsWith
Returns true if a string ends with another string passed as parameter.

	a.endsWith("where"); // returns false

####contains
Returns true if a string contains another string passed as parameter.

	a.contains("me"); // returns true
####replace
Replaces all occurances of a string within another string with a new one.

	var s = "something somewhere",
	    old = "some",
	    new = "any";
	s.replaceAll(old, new);

All functions ignores cases. <code><b>true</b></code> can be passed as the last param for case sensitive operation.
