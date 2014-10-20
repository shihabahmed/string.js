#string.js
A few javascript functions for working with strings.

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
####format
Formats string

	var str = "{0} is greater than {1}";
	str = str.format(10, 6); // str = "10 is greater than 6"

All functions (except <code>format</code>) ignores cases. <code><b>true</b></code> can be passed as the last param for case sensitive operation.
