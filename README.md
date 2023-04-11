# arithmetic-formatter
This is a Free Code Camp project which can be foud in https://www.freecodecamp.org/learn/scientific-computing-with-python/scientific-computing-with-python-projects/arithmetic-formatter

''
This project must take a list of arithmetic problems and return them displayed vertically. For that were developed four functions.

is_valid() receives as a single parameter the list of problems. That list must contain each problem as a string. The function check if the problems fit the requirements defined by the project and return either an error mensage or True.

result() receives the list of problems, convert the strings to integers and calculate the results of each problems returning a list with the results as strings.

matrix_arranger() receives the list of problems and organize them in a matrix. Then the matrix is transposed so the problems are arranged vertically. The function returns this transposed matrix.

arithmetic_arranger() receives as parameters the list of problems and a boolean value which is, by default, False. This function calls the three functions described above and if the problems are valid, it returns the problems arranged in a single string. The result() is only called if the second parameter is set to be True.
