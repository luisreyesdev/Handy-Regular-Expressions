Working with Comments
=====================

####Capture all comments. Single or multiline | [Try it out](http://www.regexr.com/3989a)
```
/[\/\*].*/g
``` 

===
**Single line comments** | [Try it out](http://www.regexr.com/3989g)
```
/(\/\/).*/g
``` 
```javascript
/*!
 * This is and example of a multi-line comment.
 */

/**
 * Removes any duplicate characters from the provided string.
 * @private
 * @param {String} str String to remove duplicate characters from.
 * @returns {String} String with any duplicate characters removed.
 */ 
 
function name( params ){
	// This is a comment in a function
	return params;	
}

```

===