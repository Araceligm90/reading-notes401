# READING NOTES 3

## Read & write files in Python:


**1. What is a file?**

It is a contiguous set of bytes used to store data. Most modern file systems are composed of three main parts:

    1. Header: metadata about the contenteos of the file (file name, size, type, etc).
    2. Data: contents of the file as written by the creater or editor.
    3. Enf of file (EOF): special character that indicates the end of the file.


**2. File paths.**

The file path is a string that represents the location of a file. It's broken into three major parts:

    1. Folder path: the file file folder location on the file system where subsequent folders are separated by a forward 
    slash / (Unix) or backslash \ (Windows).
    2. File name: the actual name of the file. 
    3. Extension: the end of the file path pre-pended with a period (.) used to indicate the file type.


**3. Opening and closing a file in Python.**

To open a file, you must do it by invoking the open() built-in function, which has a single required argument, that is 
that the path to the file has a dingle return, the file object. 
It is very important that you close the file to avoid unwanted behavior, including resource leaks. You can close a file 
by using the try-finally block or with a 'with statement', as shown below:

    1. reader = open('dog_breeds.txt')
        try:
        # Further file processing goes here
        finally:
        reader.close()

    2. with open('dog_breeds.txt') as reader:
         # Further file processing goes here


**4. File objects.**

A file object is an object exposing a file-oriented API (with methods such as read() or write()) to an underlying 
resource. 

There are three different categories of file objects:

    1. Text files.
    2. Buffered binary files: used for reading and writing binary files. 
    3. Raw binary files: generally used as a low-level building-block for binary and text streams.






