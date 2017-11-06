# regEx
What is the RegExp:
	regexp stands for "Regular Expressions", which is an object that describes a pattern of 	characters. Syntax {/pattern/modifiers}


For example,
	var patt = /zoey/i;

Explanation:
	zoey --> is a pattern (to be used in a search)
	i --> is a modifier to perform case-insensitive matching.

Other modifires
	g --> is a modifier to perform a global match.
	m --> is a modifier to perform multiline matching.

How to use RegExp:

-Brackets:
A) /[]/g will find all the characters between the brackets.

For example,
	var str = "I'm doing a research";
    	var patt1 = /[a]/g;
    	var result = str.match(patt1); //will return all a's in the string.

Another example,
	var str = "I'm doing a research, again.";
	var patt1 = /[ai]/g;
	var result = str.match(patt1); //will return ALL a's and i's in the string.


B) /[^]/g will find all the characters except the ones between the brackets.

For example,
	var str = "Stay away from the bees!";
    	var patt1 = /[^b]/g;
    	var result = str.match(patt1); //will return ALL characters except (b)

C) /[0-6]/g will find all numbers between 0-6

D) /[^0-6]/g will return any numbers NOT between 0-6



.	Find a single character, except newline or line terminator.	 
\w	Find a word character or a digit.
\W	Find a non-word and non-digit character.
\d	Find a digit.
\D	Find a non-digit character.


Find more at https://www.w3schools.com/jsref/jsref_obj_regexp.asp
