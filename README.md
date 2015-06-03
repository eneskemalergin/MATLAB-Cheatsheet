# MATLAB

--- 
## Shortcuts
> clear : Clears the variables in workspace
> clc : Clears the command window

## Built-in Functions
> pi : represents for pi

```MATLAB
x = pi/5
# 0.6283
```

MATLAB uses parentheses to pass inputs to functions, similar to standard mathematical notation.

> sin(x): sine of x
> abs(x): absolute value of x
> sqrt(x): square root of x

```MATLAB
x = pi/2
y = sin(x)
# 1
z = sqrt(-1)
# 0.0000 + 3.0000i
```

###Built-in Functions
####Elementary Math
#####Arithmetic

| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| plus	| Addition|
| uplus	| Unary plus|
| minus	| Subtraction |
| uminus |	Unary minus |
| times	| Element-wise multiplication |
| rdivide	| Right array division |
| ldivide	| Left array division | 
| power	| Element-wise power |
| mtimes	 | Matrix Multiplication |
| mrdivide	| Solve systems of linear equations xA = B for x |
| mldivide	| Solve systems of linear equations Ax = B for x |
| mpower	| Matrix power |
| cumprod	| Cumulative product |
| cumsum	| Cumulative sum |
| diff	| Differences and Approximate Derivatives |
| prod	| Product of array elements |
| sum	| Sum of array elements |
| ceil	| Round toward positive infinity
| fix	| Round toward zero
| floor	| Round toward negative infinity
| idivide	| Integer division with rounding option
| mod	| Remainder after division (modulo operation)
| rem	| Remainder after division
| round	| Round to nearest decimal or integer

#####Trigonometry

| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| sin	| Sine of argument in radians
| sind	| Sine of argument in degrees
| asin	| Inverse sine in radians
| asind	| Inverse sine in degrees
| sinh	| Hyperbolic sine of argument in radians
| asinh	| Inverse hyperbolic sine
| cos	| Cosine of argument in radians
| cosd	| Cosine of argument in degrees
| acos	| Inverse cosine in radians
| acosd	| Inverse cosine in degrees
| cosh	| Hyperbolic cosine
| acosh	| Inverse hyperbolic cosine
| tan	| Tangent of argument in radians
| tand	| Tangent of argument in degrees
| atan	| Inverse tangent in radians
| atand	| Inverse tangent in degrees
| atan2	| Four-quadrant inverse tangent
| atan2d	| Four-quadrant inverse tangent in degrees
| tanh	| Hyperbolic tangent
| atanh	| Inverse hyperbolic tangent
| csc	| Cosecant of input angle in radians
| cscd	| Cosecant of argument in degrees
| acsc	| Inverse cosecant in radians
| acscd	| Inverse cosecant in degrees
| csch	| Hyperbolic cosecant
| acsch	| Inverse hyperbolic cosecant
| sec	| Secant of angle in radians
| secd	| Secant of argument in degrees
| asec	| Inverse secant in radians
| asecd	| Inverse secant in degrees
| sech	| Hyperbolic secant
| asech	| Inverse hyperbolic secant
| cot	| Cotangent of angle in radians
| cotd	| Cotangent of argument in degrees
| acot	| Inverse cotangent in radians
| acotd	| Inverse cotangent in degrees
| coth	| Hyperbolic cotangent
| acoth	| Inverse hyperbolic cotangent
| hypot	| Square root of sum of squares

#####Exponents and Logarithms

| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
|exp	| Exponential
| expm1	| Compute exp(x)-1 accurately for small values of x
| log	| Natural logarithm
| log10	| Common logarithm (base 10)
| log1p	| Compute log(1+x) accurately for small values of x
| log2	| Base 2 logarithm and dissect floating-point numbers into exponent and mantissa
| nextpow2	| Exponent of next higher power of 2
| nthroot	| Real nth root of real numbers
| pow2	| Base 2 power and scale floating-point numbers
| reallog	| Natural logarithm for nonnegative real arrays
| realpow	| Array power for real-only output
| realsqrt	| Square root for nonnegative real arrays
| sqrt	| Square root

#####Descriptive Statistics

| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
|corrcoef	Correlation coefficients
| cov	| Covariance
| max	| Largest elements in array
| cummax	| Cumulative maximum
| mean	| Average or mean value of array
| median	| Median value of array
| min	| Smallest elements in array
| cummin	| Cumulative minimum
| mode	| Most frequent values in array
| std	| Standard deviation
| var	| Variance
| histcounts	| Histogram bin counts
| discretize	| Group numeric data into bins or categories

#####Complex Numbers
#####Discrete Math
#####Polynomials
#####Special Functions
#####Cartesian Coordinate System Conversion
#####Constants and Test Matrices

####Linear Algebra
#####Matrix Operations
#####Linear Equations
#####Matrix Decomposition
#####Eigenvalues and Singular Values
#####Matrix Analysis
#####Matrix Functions

####Random Number Generation

####Interpolation
#####1-D Interpolation
#####Gridded Data Interpolation
#####Scattered Data Interpolation

####Optimization

####Numerical Integration and Differential Equations
#####Ordinary Differential Equations
#####Boundary Value Problems
#####Delay Differential Equations
#####Partial Differential Equations
#####Numerical Integration and Differential Equations

####Fourier Analysis and Filtering

####Sparse Matrices
#####Sparse Matrix Creation
#####Sparse Matrix Multiplication
#####Reordering Algorithms
#####Sparse Linear Algebra
#####Linera Equations(Iterative Method)
#####Graph and Tree Algorithms

####Computational Geometry
#####Triangular Representation
#####Delaunay Triangulation
#####Spatial Search
#####Bounding Regions
#####Voronoi Diagrams
#####Elementary Polygons

> x = x'    ->Takes the transpose of a vector x
```MATLAB
x = [1:5]
# 1 2 3 4 5
x = x'
# 1
# 2
# 3
# 4
# 5
```



> rand(n) : Creates an nxn matrix
> rand(row, column) : Creates  a matrix with row and column numbers
> zeros(n) : Creates a zero matrix nxn
> zeros(row, column) : Creates  a zero matrix with row and column numbers

If you want to save your variables in MATLAB's specific file format MAT-file using the ```save``` command: 	```save filename variablename```. When you clear the workspace, you can load the variable with ```load filename```


### Indexing
We can index the data by using ```x = data(row, column)``` You can use ```end``` keyword to reference take all column or row. or you can use ```end-1``` to say that all but not the last one.

