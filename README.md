Big Decimal Math
=============
 
This unit provides an arbitrary precision BCD float number type. The usecase is performing a few arithmetic operations with the maximal possible accuracy and precision, e.g. calculating the sum of numbers from a text files, where the conversion from decimal input to binary floats would take more time than the calculation.

It can be used like any numeric type and supports:

* At least numbers between 10<sup>-2147483647</sup> to 10<sup>2147483647</sup> with 2147483647 decimal digit precision
* All standard arithmetic and comparison operators
* Rounding functions (floor, ceil, to-even, ..)
* Some more advanced operations, e.g. power and sqrt
* Accurate and precise binary float (single/double/extended) to BCD float and string conversion
* ..


See my webpage for the detailed [bigdecimalmath documentation ](http://www.benibela.de/sources_en.html#bigdecimalmath)
