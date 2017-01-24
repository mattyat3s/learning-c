#Learning C Programming Language#

This document is a collection of C reference materials and code snippets that we have learnt and want to record.

It can also be a place to set out goals.

##To Do's##
- [x] one
- [ ] two

##References##
* [GNU C tutorial](http://www.crasseux.com/books/ctutorial/)
    * from this stackoverflow ticket - [Online C reference manuals](http://stackoverflow.com/questions/190006/online-c-reference-manuals)

##Snippets##

####Build and Run####

To build the c program write `make <filename-without-extension>`.

    make p1_1
    
To run the program file that the above creates write `./<filename-without-extension>`.

    ./p4.4

####Arrays####
https://www.tutorialspoint.com/cprogramming/c_arrays.htm

####Boolean Variables####
There are three options mentioned [here](http://stackoverflow.com/a/1921557), I've used the below.

    typedef enum { false, true } bool;
    
####Char Variables####

    char x = 'x';

####String Variables####
Individual characters are enclosed in single quotes, like this: 'a', and have the variable type char. On the other hand, string values are enclosed in double quotes, like this: "abcdefg". String variables are either arrays of type char or have the type "pointer to char", that is, char *.
[more on this here](http://www.crasseux.com/books/ctutorial/Conventions-and-declarations.html#Conventions%20and%20declarations)

Variable:

    char* x = "hello world";
    
Function:

    char* string() {
      return "aasdasdasdsdasdasdasdasdasdjhsdfhjshkfskhfskhsdfjhkfsdhjdsbjn";
    }
    
    char* x = string();

Print:

    printf("Hello %s\n", x);
