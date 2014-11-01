# MatrixCalc

## Specification

MatrixCalc is a graphical matrix calculator written in Java.

### About

The app will make it really easy to work with matrices (*given a size limit*). The app will be able to **load** matrices from text files and also **store** matrices in `.mtx` files. You can create **arbitrary sized** matrices (*with a specified maximum*) and perform operations on them.
There will be two types of data you can make operations on: **scalars** and **matrices.** Between them you can perform **addition**, **substraction** and **multiplication.** You can also obtain informations from a matrix: **dimension**, **rank**, **determinant** and its **transpose.**

### Look

The UI will consist of three main parts:

* A **large result matrix** that displays the result of the actual operation. This result can be saved to a `.mtx` file. The matrices in the app will be simple and clean tables, you can navigate in them, not by just clicking, but with arrow keys also.
* **Two smaller areas** for the matrices and scalars. There will be a *switch* to change between matrix and scalar type. The size of the matrix can be changed dynamically by adding and removing columns and rows with **+/-** buttons. Below these will be displayed the **properties of the matrices** in text fields (dimension, rank and determinant). 
* There will be a **control panel** part where the other tasks can be performed. These will include store and load button and identity matrix shortcut, transpose calculation. You will be able to load the result matrix in one of the two smaller matrices to continue calculating with it.

Every operation, that cannot be evaluated (e.g. incorrect matrix size), **error messages** will be presented to the user. The details of the matrices will be calculated dynamically (except maybe the determinant, because of performance issues). The app will be as simple and as fast possible.
