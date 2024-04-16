# Python learning notes

use global keyword to create a global variable from a function
Text Type:	str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
None Type:	NoneType


##The list() Constructor
thislist = list(("apple", "banana", "cherry")) # note the double round-brackets

List is a collection which is ordered and changeable. Allows duplicate members.
Tuple is a collection which is ordered and unchangeable. Allows duplicate members.
Set is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.
Dictionary is a collection which is ordered** and changeable. No duplicate members.

##List comprehension
newlist = [expression for item in iterable if condition == True]


##Unpacking a Tuple

fruits = ("apple", "banana", "cherry")

(green, yellow, red) = fruits

###Note: The number of variables must match the number of values in the tuple, if not, you must use an asterisk to collect the remaining values as a list.

##Using Asterisk*
fruits = ("apple", "banana", "cherry", "strawberry", "raspberry")
(green, yellow, *red) = fruits


##sets
add into a set using update() method
remove from a set using discard() -> will not raise error, or remove() -> will raise error if item does not exist

