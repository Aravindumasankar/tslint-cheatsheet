# tslint-cheat-sheet
Cheat Sheet For TS lint

| RULE NAME                                                         |       ACTIONS TAKEN                            |
| :---------------------------------------------------------------- | ---------------------------------------------: |         
| ' should be " (quotemark)	                                        |       replace ' to  "	
| != should be !== (triple-equals)tslint(1)	                        |       rplace != to !==	
| == should be === (triple-equals)tslint(1)	                        |       relace == to ===	
| Array type using 'Array<T>' is forbidden for simple types.Use 'T[]' instead. (array-type)    |	      convert Array<obj>= [] to obj[]	
| Array type using 'T[]' is forbidden for non-simple types.Use 'Array<T>' instead. (array-type)     |       convert B<int>[] = [] to Array<B<int>>	
| block is empty (no-empty)tslint(1)	                              |       comment //empty inside the block.	
| Calls to 'console.log' are not allowed. (no-console)	            |       remove console.log lines.	
| Consecutive blank lines are forbidden (no-consecutive-blank-lines)|       remove blank lines.	
| Correct one of the identical sub-expressions on both sides of operator "&&" (no-identical-expressions)tslint(1)    |  remove identical code from if loop eg:- if(a && a)=> if(a)
| custom info method: Adds additional meta information to the meta-section of the log and logs to custom logger. Exceeds max line length of 120.	      |	    make it into more lines.
| define a constant instead of duplicating this literal 3 times. (no-duplicate-string)   |	    create a new variable and assign that literal to it and use variable in code.
| Don't use 'Object' as a type. Avoid using the `Object` type. Did you mean `object`? (ban-types)     |	    disable the rule.	
| Expected a 'for-of' loop instead of a 'for' loop with this simple  iteration (prefer-for-of)tslint(1) |	    convert for loop to for-of loop	
| expected property shorthand in object literal ('{err}').   (object-literal-shorthand)tslint(1)       |	    disable the rule.solution-change uri:uri to uri.
| file should end with a newline (eofline)	                        |       end code with a new line	
| Forbidden 'var' keyword, use 'let' or 'const' instead (no-var-keyword)            | 	    change var to let	
| Immediately return this expression instead of assigning it to the temporary variable "emptyArray".(prefer-immediate-return)tslint(1) |   	return expression directly without declaration. like return []; or return {....};
| Import sources within a group must be alphabetized. (ordered-imports)tslint(1)        |	    arrange import statements alphabetically.	
| interface name must start with a capitalized I (interface-name)	  |       start interface name with I	
| Merge this if statement with the enclosing one. (no-collapsible-if)tslint(1)                |	    merge if statements	
| Missing radix parameter (radix)tslint(1)	                        |       disable the rule.	
| Missing semicolon (semicolon)tslint(1)                            |   	end line with ;	
| missing trailing comma	                                          |       end with comma	
| no unused expression                                              |   	disable the rule.	
| non-arrow functions are forbidden (only-arrow-functions)          |   	remove function keyword and use () => {} 	
| object access via string literals is disallowed(no-string-literal)|   	create a new variable and assign that string to it. (["uri"] to [uri] where uri: string= "uri")	
| parameters are not aligned (align)tslint(1)                       |   	align parameters.	
| Parentheses are required around the parameters of an arrow   function definition (arrow-parens)tslint(1)      |	    make parentheses.	
| Remove this commented out code. (no-commented-code)tslint(1)	    |       remove comment.	
| Remove this useless assignment to local variable "bind".(no-dead-store)          |		disable this rule.
| require statement not part of an import statement(no-var-requires)|   	write import statement instead of var ..= require()
| Shadowed variable: 'response' (no-shadowed-variable)	            |       rename the parameter of function and use in code.
| Simplify this expression. (no-redundant-boolean)	                |       use if else for simplification.	
| statements are not aligned	                                    |       align statements	
| The key  is not sorted alphabetically (object-literal-sort-keys)	|       arrange keys alphabetically.	
| Type assertion using the '<>' syntax is forbidden. Use the 'as'  syntax instead. (no-angle-bracket-type-assertion)  |	    convert <any>object to "object as any"
| Unnecessarily quoted property 'data' found.(object-literal-key-quotes)                       |   	disable the rule.
| Unnecessary initialization to 'undefined'. (no-unnecessary-initializer)                       |   	remove initialisation.	
| unused expression, expected an assignment or function call (no-unused-expression)	      |   	disable the rule.
| use 'string' instead of String	                    	        |       replace with string.
| Use 'undefined' instead of 'null' (no-null-keyword)tslint(1)      |       disable.	
| variable name must be in lowerCamelCase, PascalCase or UPPER_CASE (variable-name)tslint(1) |	    Convert variable name into camelCase.	
  
