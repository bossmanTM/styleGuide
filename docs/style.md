# Common Style
All ambiguities should be emailed to chase@jackman.nz and temporarily resolved using 
the [linux kernel coding style](https://www.kernel.org/doc/html/v4.10/process/coding-style.html)
## Indentation
Tabs are 1 tab. We do not use spaces for indentation here as there is a character specifically designed for it.
This allows the indentation to be adjusted to whatever each programmer likes while maintaining a readable codebase.

Spaces will be used with a width of 4 for anything that follows an existing bit of text.
## Line length
The soft limit on line length is 80 columns and the hard limit is 160 assuming tabs to have a width of 4.
This limit is not strictly enforced and making lines finish what they are saying is more valueable than a shorter line
(this is taken advantage of severely in this spec)

## Placing of Braces
Braces should be placed on the same line as if statements, function declarations and all related.
There is almost no cases where a line containing only a brace is reasonable.

## Naming
We do not care about making function and class names absurdy short.
The only strict enforcement about names is that things must be named in a manner that makes it understandable.

Function names should use underscores in place of spaces and use lowercase except when reasonable not to.  

Preprocessor macros should use underscores in place of spaces and be all capitals.

Variables should use lowercase on the first letter and uppercase for the start of all words.

Classes, Structs, etc should use upper CamelCase
