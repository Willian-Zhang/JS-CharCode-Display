JS-CharCode-Display
===================

Display or Convert String to Hex Char Code

# Implementation
	<script src="char-code.js"></script>
	
# Example
	"SomeString".getCharString();
# or
	"SomeString".getCharArray();
	
# APIs:
	String.prototype.getCharString = function (colPerRow,separator,lineSeparator,withPrefix,isUTF16,callback);
	String.prototype.getCharStringInOneLine = function (separator,withPrefix,isUTF16);
	String.prototype.getCharArray = function (colPerRow,withPrefix,isUTF16,callback);
	String.prototype.getCharArrayInOneLine = function (withPrefix,isUTF16);
	
All arguments are optional
