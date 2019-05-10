# Mastering Python

<a href="https://www.packtpub.com/application-development/mastering-python?utm_source=github&utm_medium=repository&utm_campaign=9781785289729 "><img src="https://d255esdrn735hr.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/I9729.jpg" alt="Mastering Python" height="256px" align="right"></a>

This is the code repository for [Mastering Python](https://www.packtpub.com/application-development/mastering-python?utm_source=github&utm_medium=repository&utm_campaign=9781785289729 ), published by Packt.

**Master the art of writing beautiful and powerful Python by using all of the features that Python 3.5 offers**

## What is this book about?
Python is a dynamic programming language. It is known for its high readability and hence it is often the first language learned by new programmers. Python being multi-paradigm, it can be used to achieve the same thing in different ways and it is compatible across different platforms. Even if you find writing Python code easy, writing code that is efficient, easy to maintain, and reuse is not so straightforward.

This book covers the following exciting features:
Create a virtualenv and start a new project 
Understand how and when to use the functional programming paradigm 
Get familiar with the different ways the decorators can be written in 
Understand the power of generators and coroutines without digressing into lambda calculus 
Create metaclasses and how it makes working with Python far easier 
Generate HTML documentation out of documents and code using Sphinx 
Learn how to track and optimize application performance, both memory and cpu 
Use the multiprocessing library, not just locally but also across multiple machines 
Get a basic understanding of packaging and creating your own libraries/applications 

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1-785-28972-1) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
import abc
import importlib
class Plugins(abc.ABCMeta):
 plugins = dict()
 def __new__(metaclass, name, bases, namespace):
 cls = abc.ABCMeta.__new__(
 metaclass, name, bases, namespace)
```

**Following is what you need for this book:**
Almost anyone can learn to write working script and create high quality code but they might lack a structured understanding of what it means to be 'Pythonic'. If you are a Python programmer who wants to code efficiently by getting the syntax and usage of a few intricate Python techniques exactly right, this book is for you.

With the following software and hardware list you can run all code files present in the book (Chapter 1-).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-15 | Python 3.3+, Python 3.5 recommended | Windows, Mac OS X, and Linux (Any) |



We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it]().


## Get to Know the Author
**Rick van Hattem**
Rick van Hattem is an experienced programmer, entrepreneur, and software/database architect with over 20 years of programming experience, including 15 with Python. Additionally, he has a lot of experience with high-performance architectures featuring large amounts of concurrent users and/or data.
Rick has founded several start-ups and has done consulting for many companies, including a few Y Combinator start-ups and several large companies. One of the startups he founded, Fashiolista.com, is one of the largest social networks for fashion in the world, featuring millions of users and the performance challenges to accompany those.Rick was one of the reviewers on the book PostgreSQL Server Programming,
Packt Publishing.


## Other books by the authors
[Python: Journey from Novice to Expert](https://www.packtpub.com/application-development/python-journey-novice-expert?utm_source=github&utm_medium=repository&utm_campaign=9781787120761 )


### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.



