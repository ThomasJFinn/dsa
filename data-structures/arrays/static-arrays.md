## Static arrays

An array is one the most fundamental data structures in computer science. 
Arrays store information that is accessed via an index. 
For example, an array with five values stored is displayed below.

| Index | Value |
|:- | -: |
|0  | 12 |
|1 | 3 |
|2| 2 |
|3 | 43|
|4 | 1 |

If you want to access the fourth element of an array, you just look at entry with index value of 3.
That is, you don't have to *sequentially* look through the array.
Hence an array is useful for retrieving values when you know the corresponding index.

There are two important considerations for building arrays:
 * Arrays are stored as contiguous blocks of memory. 
 * The size of the array must be explicitly set upon creation to store in memory.

To create our array above we would have to declare we are creating an array with five elements. 
We would be extremely efficient with our memory allocation but would not be able to add more elements to the array without deeper consideration.

An array is *static* if the size is declared upon creation.
An array is *dynamic* if the size is permitted to change to account for the insertion or deletion of many new entries.

### Initializing a static array

You need to fix the size of a static array explicitly at initialization.
When initializing we must assign valid values for each index.
A valid value can be empty. 
For example, Python uses the `None` value as a placeholder.