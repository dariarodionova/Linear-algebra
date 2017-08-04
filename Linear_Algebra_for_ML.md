## Table of contents  

- **[Vector](#Vector)**  
		1.[Unit Vector](#UnitVector)  
        2.[Orthogonal Vector](#OrthogonalVector)  
        3.[Orthonormal Vector](#OrthonormalVector)  
- **[Matrix](#Matrix)**  
		1.[Identity Matrix](#IdentityMatrix)  
        2.[Diagonal Matrix](#DiagonalMatrix)  
        3.[Matrix Transpose](#MatrixTranspose)  
        4.[Symmetric Matrix](#SymmetricMatrix)  
        
- **[Tensor](#Tensor)**


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
    <a name="DiagonalMatrix">  
      
-	### Diagonal matrix _(Диагональная матрица)_
	Diagonal matrix has values on the main diagonal and zeros everywhere else. Matrix is diagonal **if and only if** Dij = 0 for all i **unequal** to j. A **rectangular** matrix can also be diagonal.     
	![Matrix](/Images/DiagonalMatrix.png)  
    </a>
    <a name="MatrixTranspose">  
    
 -	### Matrix transpose _(Транспонированная матрица)_  
 	A transpose is an operation of mirroring a matrix across **main diagonal** (from upper left corner to a 	lower right corner).  
 	![Formula](/Formulas/f11.png)  
 	![Formula](/Formulas/f12.png)  
  	![Matrix](/Images/MatrixTranspose.gif)
 	</a>
	<a name="SymmetricMatrix"> 

-	### Symmetric matrix _(Симметричная матрица)_
	A symmetric matrix is a matrix that is **equal** to it's **own transpose**.  
	![Formula](/Formulas/f8.png)  
	![Matrix](/Images/SymmetricMatrix.gif)  
    
     </a>   

# Tensor _(Тензор)_ 
An array of numbers arranged on a regular grid with a variable number of axes. Ex.: 3-D matrix:  
![Formula](/Formulas/f7.png)  
![Tensor](/Images/Tensor.png) 

# Matrix as a linear
A matrix can be understood as a certain linear transforamtion of space.  
There are diffrent kinds of transformations, like: rotation, sheer, scaling etc.  
![LinearTransformation](/Images/SpaceRotation.png)  
![LinearTransformation](/Images/SpaceScale.png)

     
-	### Singular matrix _(Вырожденная, особенная, сингулярная матрица)_
	A square matrix is singular if it has **no inverse**, because it's **determinant** equals **0**.  
  	![Formula](/Formulas/f13.png)  
    All of these matrices are singular:  
    ![Formula](/Formulas/f14.png)  
  	![Matrix](/Images/SingularMatrix.gif) 
