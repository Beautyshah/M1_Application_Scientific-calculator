# Requirements
## Introduction
  * Mathematical operations are a part of our daily lives. Everyday we will be involving with various types of calculations around us. Matrices is a mathematical entity where numbers are arranged in rows and columns. A lot of applications exist with matrices in real life.The major application lies in the software industry such as development of algorithms like path finder algorithms, image processing algorithms and many more.
  * In this project, some of the basic matrix operations are presented where a user can select the operation to be performed on the matrix. Then the matrices with their size are entered. Note that only square matrices are being considered for the project.

## Research

### Objective
This project focuses on matrix operations on square matrices. The operations performed on a pair of square matrices are, addition, subtraction and multiplication. The operations performed on a single square matrix are, transpose, determinant and inverse. 

### Benefits

A user who is working on a laptop or a desktop who would be working on matrix based calculations, can make use of this application as handy. A human being can find the output values of a matrix for a maximum of size 3 X 3, i.e 3 rows and 3 columns. If they try to solve the matrix for dimensions above 3 , the time consumed is large and verification that the solution is correct or not consumes extra time. Hence this tool can be used to cross check the matrix operations conducted.


## Cost and Features

 * The cost for implementing a project involving matrix calculations is minimal to none. But the extension of matrix applications to various state of the art domains like machine learning, image processing, cryptography , path finder algorithms etc will have a research and development being done. And for the required calculations related to matrices, this program comes in handy.
 
 ### Some of The features of the project

 * This program has dynamic memory allocation involved for allocating memory for the matrices, i.e 2 dimensional arrays. A structure is implemented for storing the input matrices. The user can select the opeation to be performed by pressing a number on the keyboard. The significance of each number, i.e the operation which it performs will be displayed on the screen during the execution of the program.


## Defining Our System
* The system on the whole is viewed as a blackbox which accepts input of a single number. Then the mapping of the number is done so as to perform the appropriate function. Then the user will be prompted to enter the matrix size. After that the user is prompted to enter the matrix elements. The input is stored in 2D arrays which are dynamically allocated and passed to the respective functions. Then the output is printed on the screen. This whole process is in a loop until the user presses a key which will exit the program.

## SWOT ANALYSIS
### Strength
- To find the sum,differnces,product on a pair of matrices.
- To find the determinant,transpose and inverse of a single matrix.
### Weakness
- Restricted to only square matrices.
- Limited number of operations defined.
- The maximum size of the matrix is restricted to the maximum value of int 
### Opportunities
- Opportunity to solve large matrix problems faster.
- Saves time on solving matrix problems in research applications.
### Threats
- Possible memory leaks.
- Same Application
# 4W&#39;s and 1&#39;H

## Who:
 * Students who want to solve matrix related problems for their academic work
 * Datascience workers working on machine learning and deep learning applications which majorly involve matrices.
 * Software engineers
 * Researchers and mathematicians

## What:
 * Calculate the sum, differemce, product of two matrices and also the determinnt, transpose and inverse of a single matrix.


## When:
 * Students facing a difficulty in solving a matrix related problem, can use this program to conform their outputs.
 * Researchers can use it for getting a quick calculation output.
 * Comes to a great use when calculating for matrices of huge order.

## Where:
 * Students, employees and researchers all over the world.

## How:
 * This program can be executed in a system which has Linux or Windows operating system. 

## High Level Requirements: 
| HLR | Description |  
| ----- | ----- | 
| HR01 | User shall be able to specify the size of the matrix |
| HR02 | User shall be able to add the matrices| 
| HR03 | User shall be able to subtract the matrices| 
| HR04 | User shall be able to multiply the matrices | 
| HR05 | User shall be able to find determinant, transpose and inverse of a matrix | 

##  Low level Requirements:
 
| LLR | Description | 
| ------ | --------- | 
| LR01 | User must specify the size of the matrix,,- The size specified is the dimensions of the square matrix |
| LR02 | Addition of two matrices can be done. Both the matrices need to be of same size.,,- The size entered in the begining is same for both the matrices | 
| LR03 | Subtraction of two matrices is implemented in the same manner as addition| 
| LR04 | Multiplication of two matrices is done on two square matrices of a specified size| 
| LR05 | The determinant of a single matrix of a specified size is implemented|
