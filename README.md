AIM: To study and implement the Set data structure in Python and perform different set operations such as adding elements, removing elements, and performing union, intersection, and difference operations.

THEORY: A set in Python is an unordered collection of unique elements. It is used to store multiple values without repetition. Sets are mutable, which means elements can be added or removed after creation. However, sets do not support indexing because they are unordered.

Python provides several built-in methods and operators to perform operations on sets:

add() is used to add a single element to a set

update() is used to add multiple elements to a set

remove() or discard() is used to delete elements from a set

Union (| or union()) combines elements from both sets

Intersection (& or intersection()) returns common elements in both sets

Difference (- or difference()) returns elements present in the first set but not in the second

Symmetric Difference (^ ) returns elements that are present in either set but not in both

Sets are very useful when duplicate values need to be eliminated and when mathematical set operations are required.

ALGORITHM 1: CREATE A SET AND DISPLAY ITS ELEMENTS

Start

Create a set with required elements

Print the set

Stop

ALGORITHM 2: ADD AN ELEMENT INTO A SET

Start

Create a set with initial elements

Input the element to be added

Use add() method to insert the element into the set

Display the updated set

Stop

ALGORITHM 3: ADD MULTIPLE ELEMENTS INTO A SET

Start

Create a set with initial elements

Create another set/list containing new elements

Use add() method to add multiple elements

Display the updated set

Stop

ALGORITHM 4: REMOVE AN ELEMENT FROM A SET

Start

Create a set with initial elements

Input the element to be removed

Remove the element using remove() or discard()

Display the updated set

Stop

ALGORITHM 5: FIND UNION OF TWO SETS

Start

Create two sets A and B

Perform union operation using A | B or A.union(B)

Store the result in a variable

Display the union set

Stop

ALGORITHM 6: FIND INTERSECTION OF TWO SETS

Start

Create two sets A and B

Perform intersection using A & B or A.intersection(B)

Store the result in a variable

Display the intersection set

Stop

ALGORITHM 7: FIND DIFFERENCE OF TWO SETS

Start

Create two sets A and B

Perform difference using A - B or A.difference(B)

Store the result in a variable

Display the difference set

Stop

ALGORITHM 8: FIND SYMMETRIC DIFFERENCE OF TWO SETS

Start

Create two sets A and B

Perform symmetric difference using A ^ B or A.symmetric_difference(B)

Store the result in a variable

Display the symmetric difference set

Stop

CONCLUSION: Thus, we have successfully studied and implemented Python set operations. We learned how to create sets, add and remove elements, and perform operations like union, intersection, and difference, which help in handling unique data efficiently.
