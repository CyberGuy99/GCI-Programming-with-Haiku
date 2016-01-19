1. Other cool String manipulators:
    * uppercase - This makes all text come UPPERCASE, which can be useful if you want the user input to be all caps to ignore case sensitivity.
    * unitbuf - This flushes the file like the regular *flush* manipulator excepts flushes the file after each insertion.
    * showpoint - This can show decimal points and *no* can be added in front of it to remove decimal points.
    * showpos - This shows positive signs for all numbers and *no* can be added in front of it to show negative signs.
    * scientific - This converts all numbers to scientific notation, which is useful when dealing with large or small numbers.
    * left - This aligns all text to the left by adding padding at the right position.
    * right -  This aligns all text to the right by adding padding at the left position.
    * internal - This aligns text a certain way by adding padding in the middle position (some text go right, while others go left).
    
2. Because we are trying to design a record with a fixed size and accessing data would be important, I would use a vector. The main drawback for vectors is that adding elements would be slow, but that would not matter since there is a fixed size. Vectors are also really good at accessing elements by index and iterating by order. We can read the whole vector by using the data() function and individual elements by using the at() function. Writing can also be done by using a pointer, **p*, to point at a position and setting *p to a value.
