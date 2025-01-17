## Python Install

Many PCs and Macs will have python already installed.

To check if you have python installed on a Windows PC, search in the start bar for Python or run the following on the Command Line (cmd.exe):

C:\Users\_Your Name_>python --version

To check if you have python installed on a Linux or Mac, then on linux open the command line or on Mac open the Terminal and type:

python --version

If you find that you do not have Python installed on your computer, then you can download it for free from the following website: [https://www.python.org/](https://www.python.org/)

---

## Python Quickstart

Python is an interpreted programming language, this means that as a developer you write Python (.py) files in a text editor and then put those files into the python interpreter to be executed.

The way to run a python file is like this on the command line:

C:\Users\_Your Name_>python helloworld.py

Where "helloworld.py" is the name of your python file.

Let's write our first Python file, called helloworld.py, which can be done in any text editor.

helloworld.py

print("Hello, World!")

Simple as that. Save your file. Open your command line, navigate to the directory where you saved your file, and run:

C:\Users\_Your Name_>python helloworld.py

The output should read:

Hello, World!

Congratulations, you have written and executed your first Python program.

---

---

## W3Schools' Python Editor

We have an online Python editor where you can execute your own Python code and see the result:

### Example[Get your own Python Server](https://www.w3schools.com/python/python_server.asp "W3Schools Spaces")

Try our online Python editor:

print("Hello, World!")

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_helloworld)

This editor will be used in the entire tutorial to demonstrate the different aspects of Python.

## Python Version

To check the Python version of the editor, you can find it by importing the `sys` module:

### Example

Check the Python version of the editor:

import sys  
  
print(sys.version)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_sys_version)

You will learn more about importing modules in our [Python Modules](https://www.w3schools.com/python/python_modules.asp) chapter.

---

## The Python Command Line

To test a short amount of code in python sometimes it is quickest and easiest not to write the code in a file. This is made possible because Python can be run as a command line itself.

Type the following on the Windows, Mac or Linux command line:

C:\Users\_Your Name_>python

Or, if the "python" command did not work, you can try "py":

C:\Users\_Your Name_>py

From there you can write any python, including our hello world example from earlier in the tutorial:

C:\Users\_Your Name_>python  
Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32  
Type "help", "copyright", "credits" or "license" for more information.  
>>> print("Hello, World!")

Which will write "Hello, World!" in the command line:

C:\Users\_Your Name_>python  
Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32  
Type "help", "copyright", "credits" or "license" for more information.  
>>> print("Hello, World!")  
Hello, World!

Whenever you are done in the python command line, you can simply type the following to quit the python command line interface:

exit()

---