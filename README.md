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
|corrcoef	| Correlation coefficients
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
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| abs	| Absolute value and complex magnitude
| angle	| Phase angle
| complex	| Create complex array
| conj	| Complex conjugate
| cplxpair	| Sort complex numbers into complex conjugate pairs
| i	| Imaginary unit
| imag | Imaginary part of complex number
| isreal	| Determine whether array is real
| j	| Imaginary unit
| real	| Real part of complex number
| sign	Signum function
| unwrap	| Correct phase angles to produce smoother phase plots
#####Discrete Math
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| factor	| Prime factors
| factorial	| Factorial of input
| gcd	| Greatest common divisor
| isprime	| Determine which array elements are prime
| lcm	| Least common multiple
| nchoosek	| Binomial coefficient or all combinations
| perms	| All possible permutations
| primes	| Prime numbers less than or equal to input value
| rat	| Rational fraction approximation
| rats	| Rational output
#####Polynomials
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| poly | Polynomial with specified roots
| polyder	| Polynomial derivative
| polyeig	| Polynomial eigenvalue problem
| polyfit	| Polynomial curve fitting
| polyint	| Integrate polynomial analytically
| polyval 	| Polynomial evaluation
| polyvalm	| Matrix polynomial evaluation
| residue	| Convert between partial fraction expansion and ratio of two polynomials
| roots	| Polynomial roots
#####Special Functions
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| airy 	| Airy Functions
| besselh	| Bessel function of third kind (Hankel function)
| besseli	| Modified Bessel function of first kind
| besselj	| Bessel function of first kind
| besselk	| Modified Bessel function of second kind
| bessely	| Bessel function of second kind
| beta	| Beta function
| betainc	| Incomplete beta function
| betaincinv	|Beta inverse cumulative distribution function
| betaln	| Logarithm of beta function
| ellipj	| Jacobi elliptic functions
| ellipke	| Complete elliptic integrals of first and second kind
| erf	| Error function
| erfc	| Complementary error function
| erfcinv | Inverse complementary error function
| erfcx	| Scaled complementary error function
| erfinv	| Inverse error function
| expint	| Exponential integral
| gamma	| Gamma function
| gammainc	| Incomplete gamma function
| gammaincinv	| Inverse incomplete gamma function
| gammaln	| Logarithm of gamma function
| legendre	| Associated Legendre functions
| psi	| Psi (polygamma) function

#####Cartesian Coordinate System Conversion
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| cart2pol	| Transform Cartesian coordinates to polar or cylindrical
| cart2sph	| Transform Cartesian coordinates to spherical
| pol2cart	| Transform polar or cylindrical coordinates to Cartesian
| sph2cart	| Transform spherical coordinates to Cartesian

#####Constants and Test Matrices
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| eps	| Floating-point relative accuracy
| flintmax	| Largest consecutive integer in floating-point format
| i	| Imaginary unit
| j	| Imaginary unit
| Inf	| Infinity
| pi	| Ratio of circle's circumference to its diameter
| NaN	| Not-a-Number
| isfinite	| Array elements that are finite
| isinf	| Array elements that are infinite
| isnan	| Array elements that are NaN
| compan	| Companion matrix
| gallery	| Test matrices
| hadamard	| Hadamard matrix
| hankel	| Hankel matrix
| hilb	| Hilbert matrix
| invhilb	| Inverse of Hilbert matrix
| magic	| Magic square
| pascal	| Pascal matrix
| rosser	| Classic symmetric eigenvalue test problem
| toeplitz	| Toeplitz matrix
| vander	| Vandermonde matrix
| wilkinson	| Wilkinson's eigenvalue test matrix
####Linear Algebra
#####Matrix Operations
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| cross	| Cross product
| dot	| Dot product
| kron	| Kronecker tensor product
| surfnorm	| Compute and display 3-D surface normals
| tril	| Lower triangular part of matrix
| triu	| Upper triangular part of matrix
| transpose	| Transpose
#####Linear Equations
| Name of the Function | Job of the Function | 
| -------------------- | ------------------- |
| cond	| Condition number with respect to inversion
| condest	| 1-norm condition number estimate
| inv	| Matrix inverse
| linsolve	| Solve linear system of equations
| lscov	| Least-squares solution in presence of known covariance
| lsqnonneg	| Solve nonnegative least-squares constraints problem
| pinv	| Moore-Penrose pseudoinverse of matrix
| rcond	| Reciprocal condition number
| sylvester	| Solve Sylvester equation AX + XB = C for X
| mldivide	| Solve systems of linear equations Ax = B for x
| mrdivide	| Solve systems of linear equations xA = B for x
| cond	| Condition number with respect to inversion
| condest	| 1-norm condition number estimate
| inv	| Matrix inverse
| linsolve	| Solve linear system of equations
| lscov	| Least-squares solution in presence of known covariance
| lsqnonneg	| Solve nonnegative least-squares constraints problem
| pinv	| Moore-Penrose pseudoinverse of matrix
| rcond	| Reciprocal condition number
| sylvester	| Solve Sylvester equation AX + XB = C for X
| mldivide	| Solve systems of linear equations Ax = B for x
| mrdivide	| Solve systems of linear equations xA = B for x
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

