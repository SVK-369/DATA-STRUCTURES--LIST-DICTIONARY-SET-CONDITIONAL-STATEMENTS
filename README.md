# DATA-STRUCTURES--LIST-DICTIONARY-SET-CONDITIONAL & STATEMENTS
EXPLANATION: 
 .append ( ) adds an element to the end of a list[]
 . insert (index, element) place a value at a specific position.
 . remove (value) deletes the first occurrence of a specific value.
 . pop ( ) removes and returns the last in a list.
 .extend ( ) adds multiple elements from another list/iterable to the end .
 .sort (reverse=True) sorts elements from highest to lowest .
 .max ( ), min ( ) , and sum ( ) are built-in functions that calculate peak, lowest, and total values respectively.
 
 ACCESSING LIST ELEMENTS 
  . python lists b use 0-based indexing .
  negative  indicates like  -1 access elements starting from the right
  .list slicing syntax list[ start:stop]
  includes start and excludes stop
  . slicing with [::-1] steps backwards through the entire list to reverse it.

  
 .Dictionary (creation,modification, and access)
 .dictionaries store data in key-value pairs (key: value)
 . assign values using dict[key] = value if the key exists, it updates; not it creates a new entry .
 . keys () return all dictionary kyes, .values( ) returns all mapped values , and items() returns key-value tuple.

SETS(OPERATIONS)
.explanation /outpuit: output will  contain only distinct elements: { 'a', 'e', 'i', 'o', 'u', 'a', 'e','i'}
sets in python automatically  eliminate duplicate values and store elements in an unordered format.
ATTTEMPTING my_set[4] ='s'
EXPLANATION: This throws a type error; 'set' object does not support and assignment .sets are unordered and unindexed collections, meaning elements cannot be accessed  or changed using  
numerical indices like [4]. to add an item , use my_set.add('s').

SET OPERATIONS(UNION & INTERSECTION)
EXPLANTION: union ( )  merge elements from both sets without duplicate values .
intersection ( ) isolates elements present in both sets 
.


OPEREATORS & CONDTIONAL STATEMENTS ( IF , ELIF , ELSE )

EXPLANATION; input ( ) reads user input  as a string ; float  ( )  converts it into a decimal number for numeric comparison .
.range validation ( 0 < = score  < = 10 ) ensure valid evalutions
if ,elif, and else branches execute mutually exclusive logic blocks based on input conditions. 
