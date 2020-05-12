# MML-Companion

![alt text](https://mml-book.github.io/static/images/mml-book-cover.jpg)

## About.
This is a companion to the ‘Mathematical Foundations’ section of the book, Mathematics for Machine Learning by Marc Deisenroth, Aldo Faisal and Cheng Ong, written in python for Jupyter Notebook. Please see all resources directly related to the book on the book website: https://mml-book.github.io/. 

This companion provides implementations of figures found throughout Chapters 2 through 7, as well as additional outlines of concepts or additional figures which seemed fitting based on the context. For instance, the chapter on calculus, namely between pages 145 and 165 in Chapter 5, contain very little to no figures, for which this companion provides a few which also happen to connect with figures in Chapter 7. There are also several instances of verifying something written in the book, such as verifying (7.31), that if a function is differentiable, we can check if it is convex using the equation provided — in this same notebook is an illustration for Legendre Transform discussed at the end of this chapter. Throughout the notebooks are also comments, which are majority directly from the book, in some instances this is done to help the reader in providing an equation, e.g. whereas the book states “as in 2.24”, in example 4.1 of Chapter 4, the notebook for Chapter 4 provides 2.24.

This companion might also be helpful to anyone who might want to do their own replications, as datasets are made up or provided that aren’t explicitly stated in the book, such as the dataset for C.Elegans used to construct Example 4.7. 

Throughout the notebooks are also credits attributed to SO posts and blogs that provided guidance.

## Usage.
There are several libraries imported throughout the notebook. As a tip, you can pip install within a running notebook if you are missing any imports. The primary libraries are fairly common, such as numpy, matplotlib, and sympy, but there are some instances of more obscure libraries like networkx. 

For preview purposes, some notebooks might not render through github alone, in which case you can use https://nbviewer.jupyter.org/. 

## Errors.
There are undoubtedly errors and typos and most critically my own misunderstandings of the text. Please feel free to raise an issue here or make a pull request if you find these, it will help both of us deepen our understanding! Additionally, below is a collection of to-do’s that would enhance these notebooks greatly. 

## To-do.
1. Laplace expansion function.
2. Notebook on all the various methods for approximating eigenvalues. 
3. General multivariable Taylor expansion function.
4. A more generalized Legendre Transform function.
5. Notebook on Lagrangian multipliers. 

## Screenshots. 
![alt text](https://github.com/vbartle/MML-Companion/blob/master/screenshots/companion1.png?raw=true)
![alt text](https://github.com/vbartle/MML-Companion/blob/master/screenshots/companion2.png?raw=true)
![alt text](https://github.com/vbartle/MML-Companion/blob/master/screenshots/companion3.png?raw=true)
![alt text](https://github.com/vbartle/MML-Companion/blob/master/screenshots/companion4.png?raw=true)
![alt text](https://github.com/vbartle/MML-Companion/blob/master/screenshots/companion5.png?raw=true)
