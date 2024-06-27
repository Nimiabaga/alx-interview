Pascal's Triangle Project
Overview
This project implements a function to generate Pascal's Triangle up to a given number of rows. Pascal's Triangle is a triangular array of the binomial coefficients.

Requirements
Python 3.x
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/alx-interview.git
Navigate to the project directory:

bash
Copy code
cd alx-interview/0x00-pascal_triangle
Run the script:

bash
Copy code
python3 0-main.py
Function
pascal_triangle(n)
Generates Pascal's Triangle with n rows.

Parameters:

n (int): The number of rows in the triangle.
Returns:

List[List[int]]: A list of lists representing Pascal's Triangle.
Example
python
Copy code
>>> from 0_pascal_triangle import pascal_triangle
>>> pascal_triangle(5)
[[1], [1, 1], [1, 2, 1], [1, 3, 3, 1], [1, 4, 6, 4, 1]]
Files
0-pascal_triangle.py: Contains the pascal_triangle function.
0-main.py: A script to test the pascal_triangle function.
Testing
To test the function, run the 0-main.py script. It will print Pascal's Triangle with 5 rows:

bash
Copy code
[1]
[1, 1]
[1, 2, 1]
[1, 3, 3, 1]
[1, 4, 6, 4, 1]
Author
Julie Peters

