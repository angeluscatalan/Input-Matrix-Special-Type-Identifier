OVERVIEW

This JavaScript program accepts user input for matrix dimensions (rows and columns) and generates a matrix. The user can then choose a specific type of matrix to generate, from various common matrix types such as row matrix, column matrix, rectangular matrix, and more.
Features

The program supports the following matrix types:

Row Matrix: A matrix with only one row.

Column Matrix: A matrix with only one column.

Rectangular Matrix: A matrix where the number of rows is different from the number of columns.

Square Matrix: A matrix where the number of rows equals the number of columns.

Scalar Matrix: A square matrix where all the diagonal elements are the same, and the off-diagonal elements are zero.

Identity Matrix: A square matrix where all the diagonal elements are 1, and all off-diagonal elements are zero.

Zero Matrix: A matrix where all elements are zero.

Upper Triangular Matrix: A square matrix where all elements below the main diagonal are zero.

Lower Triangular Matrix: A square matrix where all elements above the main diagonal are zero.

HOW TO USE

1. Select Matrix Type:
First, choose the type of matrix you want to generate from the list of available matrix types. The program will ensure that the matrix you generate meets the criteria for the selected type.


2. Input Dimensions:
After selecting the matrix type, enter the number of rows and columns. Depending on the matrix type you selected, the program will validate whether the entered dimensions are valid for that type. For example, a square matrix requires equal rows and columns, while a row matrix needs exactly one row.


3. Matrix Generation:
Once the dimensions are entered, the program will generate and display the matrix based on the selected type. It will ensure the matrix follows the rules for the chosen type, such as filling diagonal elements for identity and scalar matrices or making off-diagonal elements zero for triangular matrices.
