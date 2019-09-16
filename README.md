---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 3 V2               <br/>
**Topic**:  Linear Algebra <br/>
**Amount of time**:  60 minutes  <br/>
**Author**: Laura Colon-Melendez, Greg Damico, Alison Peebles Madigan

Ported from starter repos: [link](https://github.com/learn-co-curriculum/ds-lessons-starter/tree/master/mathematic_foundations/linear_algebra) and [link](https://github.com/learn-co-curriculum/ds-lessons-starter/tree/master/mathematic_foundations/linear_algebra2)

***

#### Lesson Summary:

The lesson starts by motivating the study of linear algebra for data science by showcasing its application in problems data scientists typically solve. Next, a problem is presented to students where they have to think about how to solve a system of linear equations in 5 dimensions. This leads to a quick discussion on how to solve two dimensional systems of linear equations by hand. Before showing students how to solve systems of linear equations using Numpy, vectors and matrices are discussed. Students are shown why NumPy is used to perform arithmetic with non-scalars with a vector addition problem. Vector multiplication is introduced: the cross product of two vectors is mentioned but more attention is placed on computing the dot product of two vectors using NumPy. Matrices are introduced, including how to define matrices using NumPy, and matrix multiplication is explained -- the Hadamard product is mentioned and more time is spent discussing multiplication of two matrices using the dot product via NumPy. Students are asked to compute the shape of a NumPy array and to compute the transpose of a matrix.  Students multiply matrices and demonstrate that matrix multiplication is not commutative. Next, the inverse of a matrix is defined. After this, students solve a two-dimensional system of linear equations using NumPy, then they solve the problem posed to them at the beginning of the lesson. If time allows, simple linear regression is discussed and students solve a toy simple linear regression problem using NumPy. 



#### Topic:

Statistical Modeling - Linear Algebra

#### Learn.co material:

[Motivation for Linear Algebra in Data Science](https://github.com/learn-co-curriculum/dsc-lingalg-motivation)

[Systems of Linear Equations](https://github.com/learn-co-curriculum/dsc-lingalg-linear-equations)

[Systems of Linear Equations - Quiz](https://github.com/learn-co-curriculum/dsc-lingalg-linear-equations-quiz)

[Scalars, Vectors, Matrices, and Tensors - Code Along](https://github.com/learn-co-curriculum/dsc-scalars-vectors-matrices-tensors-codealong)

[Vectors and Matrices in Numpy - Lab](https://github.com/learn-co-curriculum/dsc-linalg-vector-matrices-numpy-lab)

[Matrix Multiplication - Code Along](https://github.com/learn-co-curriculum/dsc-linalg-mat-multiplication-codealong)

[Properties of Dot Product - Lab](https://github.com/learn-co-curriculum/dsc-linalg-dot-product-properties-lab)

[Solving Systems of Linear Equations with Numpy - Code Along](https://github.com/learn-co-curriculum/dsc-lineq-numpy-codealong)

[Solving Systems of Linear Equations with Numpy - Lab](https://github.com/learn-co-curriculum/dsc-lineq-numpy-lab)

#### Prerequisite knowledge:

Students should have a grasp of simple algebra problems and how to solve them. The focus will be on extending familiar algebraic techniques to higher-dimensional cases. 


#### Prerequisite Learn.co material:

[Introduction to NumPy](https://github.com/learn-co-curriculum/dsc-introduction-to-numpy)

[Getting Started with NumPy](https://github.com/learn-co-curriculum/dsc-getting-started-with-numpy)

[Getting Started with NumPy - Lab](https://github.com/learn-co-curriculum/dsc-getting-started-with-numpy)


#### Learning goals for this lesson:

* Students will be able to use vector addition and multiplication in NumPy

* Students will be able to explain the dot product of vectors and matrices. 

* Students can use NumPy to compute the inverse and transpose of matrices. 

* Students can use NumPy to solve systems of linear equations. 

* _Optional_: Students can use matrix algebra and NumPy to calculate the parameter values for simple linear regression. 


#### Relevant learning goals from Airtable: 

* LINEAR_ALG.1.reczfY7oGMJSfOsTa

* LINEAR_ALG.2.recoqJEZZT8sLuFhw

* LINEAR_ALG.2.recTx2fOf6IcxhM5f

* LINEAR_ALG.2.recPQEDAklOguF6oT

* LINEAR_ALG.2.rec5CRnepBfNw9h5f

* LINEAR_ALG.2.recHuCJtD9KGoig8Y

* LINEAR_ALG.2.recU5oOE3Jcgx2XJ5

* LINEAR_ALG.1.recPHVle0oj24FyR8

* LINEAR_ALG.1.recsYijcJ9OL77GDT

* LINEAR_ALG.1.recuu1meEe5QYZXFi

* LINEAR_ALG.2.rec6XhidPxKtczQoJ

* LINEAR_ALG.2.recNWsUWAkidrTCFP

* LINEAR_ALG.2.recTqePbXAk1CDfsV

#### Misconceptions / Notes

* Students may be confused by the need to add a column of 1s to the coefficients matrix when performing simple linear regression using NumPy. 

#### Materials

- Ipython notebook 

#### Vocab / Concepts 

* vectors, matrices
* transpose of a matrix
* inverse of a matrix 

#### Lesson Outline:

* Motivation to learn Linear Algebra (5 minutes) 
    * We use concepts related to linear algebra for many applications in Data Science such as NLP, computer processing, recommender systems, etc.

* Solving systems of linear equations using basic algebra (5 minutes)
    * Before we're able to solve systems of linear equations using NumPy we need to learn about vectors and matrices. 
    
* Vectors (10 minutes) 
    * Defining vectors in NumPy 
    * Adding vectors with NumPy
    * Computing the dot product of two vectors with NumPy

* Matrices (20 minutes)
    * Defining matrices in NumPy
    * Computing the shape of matrices
    * Using NumPy to compute the transpose of a matrix. 
    * Multiplying matrices with NumPy
        * Concrete problems are presented to students to solve so they understand the intricacies of matrix multiplication
            * It's important to stress that two matrices may only be multiplied together if the number of columns of the first matrix matches the number of rows of the second
            * Matrix multiplication is not commutative: this is showcased by asking students to multiply a matrix by its transpose in the two possible orders. 
    * Computing the inverse of a matrix using NumPy.

* Solving systems of linear equations using NumPy (10 minutes) 
    * Students solve systems of linear equations by computing the inverse of a matrix and also by using `np.linalg.solve`. 

* Summary (5 minutes)

Wiggle room: 5 minutes 

* Simple Linear Regression: Ordinary Least Squares and NumPy (20 minutes) 
    * For advanced groups, or if time permits, simple linear regression with OLS in NumPy is presented using a toy model. 