---
layout: post
title: Getting Started with NumPy
xcerpt_separator:  <!--more-->
---

[NumPy](https://numpy.org/) forms the backbone of many machine learning libraries in python - scikit-learn, SciPy, TensorFlow, PyTorch, MXNet, JAX and many more due to the its speed of execution, in-built data structures and functions to support linear algebra operations. I started with the goal to understand how to write code using NumPy.  

<!--more--> 

I had not explicitly tried to do this in the past, although I had a fair bit of experience working with data structured provided by Python standard library - lists, tuples, dictionaries. 

I learnt a lot related to NumPy (this just scratched the surface, there's a lot more to cover), and learnt a thing or two about some cool _new_ (the last python version I really went into was 3.4) Python features I previously did not.

Here is what I did:
* **[NumPy - Absolute Beginners Tutorial](https://numpy.org/doc/stable/user/absolute_beginners.html)**: Documentation is the place to start when learning something new. I was looking for some sort of Quickstart, Tutorial and found this page. It covers NumPy basics and is perfect for people who are familiar with Python and want to learn NumPy. I know, I know, you are not an absolute beginner, but swallow up that ego and blaze through this page to get a sense of what you can do using NumPy. You may want to read the [Quickstart tutorial](https://numpy.org/doc/stable/user/quickstart.html) too which is less wordy and covers things in detail
* **[NumPy Challenges on HackerRank](https://www.hackerrank.com/domains/python?filters%5Bsubdomains%5D%5B%5D=numpy)**: Solving these 15 odd questions will make you write some code using NumPy functions. These are not challenging questions and the descriptions of the NumPy functions to be used is provided along with examples along with the questions. Recommended to go through these to familiarize yourself with writing code using NumPy
* **Further Reading**: NumPy library has a lot of functions. I did not want to write code covering all of them as my intention was to not be a deer-in-front-of-the-headlights when I see NumPy code. Going through the above resources provided a clear understanding of the basic concepts. [More NumPy concepts and functions](https://numpy.org/doc/stable/user/quickstart.html#functions-and-methods-overview) would be tackled as and when encountered in the wild working with other data science libraries. Here are few other resources that I saved for later:
    * [100 NumPy exercises](https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises.md)
    * [From Python to NumPy book by Nicolas P. Rougier](https://www.labri.fr/perso/nrougier/from-python-to-numpy/)
    * [ML+ 101 NumPy Exercises](https://www.machinelearningplus.com/python/101-numpy-exercises-python/)


And, this is what I learnt:
* NumPy arrays - create, reshape, concatenate, flip, indexing 
* dtype - types 'int', 'float', can convert strings to desired format directly
* NumPy variety of functions - linear algebra,  polynomials
* NumPy axis - finally
* NumPy formatting printoptions

* Python regex sub
* Python unpacking operator *
    - PEP 448, and 3132
    - Using it with a , and map.
