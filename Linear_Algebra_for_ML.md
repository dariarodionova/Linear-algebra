## Table of contents  

- **[Vector](#Vector)**  
		1.[Unit Vector](#UnitVector)  
        2.[Orthogonal Vector](#OrthogonalVector)  
        3.[Orthonormal Vector](#OrthonormalVector)  
        -----------------  
        4.[Vector norm](#VectorNorm)  
        5.[Linear dependance](#LinearDependance)  
        6.[Vector addition](#VectorAddition)  
        
- **[Matrix](#Matrix)**  
		1.[Identity Matrix](#IdentityMatrix)  
        2.[Diagonal Matrix](#DiagonalMatrix)  
        3.[Matrix Transpose](#MatrixTranspose)  
        4.[Symmetric Matrix](#SymmetricMatrix)  
        
- **[Tensor](#Tensor)**  

- **[Matrix as a Linear Transformation](#LinearTransformation)**  
		1.[Matrix Inverse](#MatrixInverse)  
        2.[Determinant](#Determinant)  
        3.[Singular Matrix](#SingularMatrix)    
        4.[Nonsingular Matrix](#NonsingularMatrix)


# Scalar _(Скаляр)_
Just a simple number, ex.:
![Formula](/Formulas/f1.png)  
<br />  

<a name="Vector">  
  
# Vector _(Вектор)_
A set of numbers that can identify a point in space.   
![Formula](/Formulas/f2.png)      
![Vector](/Images/vector.png)
<br />  
<br />  

<a name="UnitVector">  
  
-	### Unit Vector _(Единичный вектор)_
	Unit vector is a vector with a unit norm (norm is a function that assigns positive length to a vector). 
	![Formula](/Formulas/f3.png)    
	![UnitVectors](/Images/UnitVectors.png) 
    <br />  
    <br />  
    </a>
    <a name="OrthogonalVector">  
-	### Orthogonal vectors _(Ортогональные векторы)_
	Vector _**x**_ and vector _**y**_ are **orthogonal** (perpendicular) to each other if![Formula](/Formulas/f4.png) (their dot product 		equals 0). If both vectors have nonzero norm and their dot product 		equals 0, then they are 			perpendicular to each other.   
	![OrthogonalVectors](/Images/OrthogonalVectors.png)
    <br />  
    <br />   
    </a>
    <a name="OrthonormalVector">
-	### Orthonormal vectors _(Ортонормированные векторы)_
	Vector _**x**_ and vector _**y**_ are **orthonormal** if they are _orthogonal_ and have _unit norm_.
    ![OrthonormalVectors](/Images/OrthonormalVectors.gif)
    <br />  
    <br />  
    <br /> 
    </a>
    
    
<a name="Matrix">  
    
# Matrix _(Матрица)_
A matrix is a 2-D set of numbers size of m*n. Ex.: 
![Formula](/Formulas/f5.png)  
![Formula](/Formulas/f6.png)  
![Matrix](/Images/matrix.png)
<br />  
<br /> 

<a name="IdentityMatrix">  
  
-	### Identity matrix _(Единичная матрица)_
	An identity matrix is such a matrix, that if we multiply a vector on **that matrix**, the vector won't change. It is also such a **square** matrix that has ones on the main diagonal and zeros everywhere else.  
	![Formula](/Formulas/f9.png)  
    ![Formula](/Formulas/f10.png)  
	![Matrix](/Images/IdentityMatrix.png)  
  </a>
  	<br />  
    <br />   
    <a name="DiagonalMatrix">  
      
-	### Diagonal matrix _(Диагональная матрица)_
	Diagonal matrix has values on the main diagonal and zeros everywhere else. Matrix is diagonal **if and only if** Dij = 0 for all i **unequal** to j. A **rectangular** matrix can also be diagonal.     
	![Matrix](/Images/DiagonalMatrix.png)  
    </a>
    <br />  
    <br />   
    <a name="MatrixTranspose">  
    
 -	### Matrix transpose _(Транспонированная матрица)_  
 	A transpose is an operation of mirroring a matrix across **main diagonal** (from upper left corner to a 	lower right corner).  
 	![Formula](/Formulas/f11.png)  
 	![Formula](/Formulas/f12.png)  
  	![Matrix](/Images/MatrixTranspose.gif)
 	</a>
    <br />  
    <br />   
	<a name="SymmetricMatrix"> 

-	### Symmetric matrix _(Симметричная матрица)_
	A symmetric matrix is a matrix that is **equal** to it's **own transpose**.  
	![Formula](/Formulas/f8.png)  
	![Matrix](/Images/SymmetricMatrix.gif)  
     </a>  
     <br />  
     <br />  

# Tensor _(Тензор)_ 
An array of numbers arranged on a regular grid with a variable number of axes. Ex.: 3-D matrix:  
![Formula](/Formulas/f7.png)  
![Tensor](/Images/Tensor.png)  
<br />  
<br />   

<a name="LinearTransformation">  

# Matrix as a linear transformation of space
A matrix can be understood as a certain linear transforamtion of space.  
There are diffrent kinds of linear transformations, like: rotation, sheer, scaling etc.  
The **matrix** on the **right** in this situation **is** a **location where unit vectors lands**.  
![Formula](/Formulas/f16.png)  
![LinearTransformation](/Images/SpaceRotation.gif)  
  
![Formula](/Formulas/f15.png)  
![LinearTransformation](/Images/SpaceScale.gif)   
<br />  
<br />  
<a name="MatrixInverse">  
  
  
 -	### Matrix Inverse _(Обратная матрица, обратное преобразование)_
	Matrix inverse is a tool that allows us to find a "backward" transformation of a given matrix.  
    ![Formula](/Formulas/f17.png)  
    If we **transformed** matrix **I using A**, we **got A**. Let's say we need to **transform A** back **to I**.  
    What matrix do we need to multiply A with to get I? Example:  
   	![MatrixInversion](/Images/MatrixInverse.gif)  
    _**Why do we need it?**_  
    It is straightforward how to solve x*c = y if we are dealing with scalars. If we are solving for x, we just multiply y by the inverse of c, which is 1/c. The same solving principle applies when solving equations with matricies and vectors, but how does the matrix inverse look like? It is another matrix with special values. 
     <br />  
     <br />  
     <a name="Determinant"> 
      
  -	### Determinant _(Определитель, детерминант)_  
  	**Determinant** is a **tool** that allows us to **learn** about **properties** of a **square matrix**. The value of the determinant can be positive, negative or zero.  
    ![Formula](/Formulas/f19.png)  
      
      
    It allows us to learn if:  
    - _**Ax = y**_ has a **unique** solution _(this happens **if and only if** determinant is **nonzero**)_ 
    - Given matrix has an **inverse** _(this happens **if and only if** determinant is **nonzero**)_  
    
    ![Determinant](/Images/Determinant.gif)     
      
    _Example_  
    ![Formula](/Formulas/f18.png)   
    A result of this transformation is a matrix that has **det = 0**. After horizontally squishing space into a line, it is impossible to tell where did we start from, because one dimention is lost and all coordinates from this dimention are now 0. Therefore resulting matrix has no inverse.  
   ![NoInverse](/Images/noInverse.gif)
     <br />  
     <br />  
    
    <a name="SingularMatrix">
     
-	### Singular matrix / Noninvertable matrix _(Вырожденная, особенная, сингулярная матрица)_
	A square matrix is singular if it has **no inverse**, because it's **determinant** equals **0**.  
  	![Formula](/Formulas/f13.png)  
    Examples of singular matrices:  
    ![Formula](/Formulas/f14.png)  
  	![Matrix](/Images/SingularMatrix.gif)   
      
    <a name="NonsingularMatrix">  
  
    
- 	### Nonsingular matrix / Invertable matrix _(Невырожденная, неособенная матрица)_
	A square matrix is **NOT** singular. It **has inverse**, because it's **determinant** is **nonzero**.  
    