# liboac

A library to support myself with AOC, Everybody codes and comparable fun

## Functions

| Name                              | Function                                                                                              |
|:----------------------------------|:------------------------------------------------------------------------------------------------------|
| **GENERAL**                       |                                                                                                       |
| **Paniccheck**                    | panics on error                                                                                       |
| **ReadLines**                     | reads a whole file into memory and returns a slice of its lines                                       |
| **RemoveSpaces**                  | removes extra whitespace from a string                                                                |
| **ReverseString**                 | returns a reversed string                                                                             |
| **SilentAtoi**                    | returns an int or panics                                                                              |
|                                   |                                                                                                       |
| **INT SLICES**                    |                                                                                                       |
| **SortIntSlice**                  | sorts an intslice                                                                                     |
| **SumSlice**                      | returns the sum of a slice                                                                            |
| **ProductSlice**                  | returns the product of a slice                                                                        |
|                                   |                                                                                                       |
| **STRINGSMATRIX**                 |                                                                                                       |
| **StringsMatrix**                 | Struct                                                                                                |
| **StringsMatrix.buildMatrix**     | method to build the matrix                                                                            |
| **StringsMatrix.printMatrix**     | method to visually validate the matrix                                                                |
| **StringsMatrix.inMatrix**        | method to validate if a point is in the matrix                                                        |
| **StringsMatrix.wordSearch**      | method to find the number of occurrences for a word in all directions, horizontal, vertical, diagonal |
| **StringsMatrix.searchDirection** | method that searches a "word" in a "direction", starting at i,j                                       |
