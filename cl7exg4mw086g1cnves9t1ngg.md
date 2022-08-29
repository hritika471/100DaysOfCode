## Array Implementation In Java

# WHAT IS AN ARRAY AND ITS USECASE?

An array is a data structure which is collection of homogeneous datatypes stored at contiguous memory locations.

***datatype [ ] variable_name = new datatype [size];***

***int [ ] rollnos = new int [5];*** or  ***int [ ] rollnos = {2, 3, 5, 7, 9};***

## INTERNAL WORKING OF AN ARRAY 

**int [ ] rollnos ;** declaration of array (rollnos are getting defined in stack) 

** rollnos = new int [5];** initialization of array (actual memory allocation happens here. Here object is being created in heap memory)

**declaration at compile time** and **initialization at runtime** this concept is known as **dynamic memory allocation** which means at runtime or execution time memory is allocated. 


### INTERNAL REPRESENTATION OF ARRAY

Internally in java memory allocation totally depends on JVM whether its continuous or not! There could be several reasons for that :

**reason1** objects are stored in heap memory 

**reason2** In JLS(Java Language Specification) is mentioned that heap objects are not continuous.

**reason3** Dynamic memory allocation hence array objects in java may not be continuous (depends on JLS)

**PROGRAM: REVERSE AN ARRAY IN JAVA** 
![Screenshot (11).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1661786605344/RJ4e6ubxZ.png align="left")

**ALGO-INTUTION**

STEP1 : TAKE ONE ARRAY PREDEFINED OR USER INPUT 

STEP2 : PRINT ORIGINAL ARRAY AS IT IS USING FOR LOOP (i=0 to i<=arrayLength)

STEP3 : PRINT A REVERSE ARRAY BY FOR LOOP WHICH STARTS FROM i=arrayLength-1 to i>=0 AND DECREMENT i IN EACH LOOPS.


**READ TILL HERE THANKS A BUNCH:)**