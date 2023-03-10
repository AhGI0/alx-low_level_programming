## 0x0A. C - argc, argv

### General
* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be compiled on Ubuntu 20.04 LTS using `gcc`, using the options -`Wall` `-Werror` `-Wextra` `-pedantic` `-std=gnu89`
* All your files should end with a new line
* A `README.md` file, at the root of the folder of the project is mandatory
Your code should use the `Betty` style. It will be checked using <a href="https://github.com/holbertonschool/Betty/blob/master/betty-style.pl">betty-style</a>.pl and <a href="https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl">betty-doc.pl</a>
*  You are not allowed to use global variables
*  No more than 5 functions per file
*  The prototypes of all your functions and the prototype of the function `_putchar` should be included in your header file called `main.h`
* Don’t forget to push your header file
* You are allowed to use the standard library


------
### Question #0
  
  What is argc?

    The length of the first command line argument

    The number of command line arguments

    A flag set to 1 when command line arguments are present

    The size of the argv array


 ---

 Question #1

What is argv[argc]?

    The last command line argument

    NULL

    It does not always exist

    The program name

    The first command line argument

---
 Question #2

In the following command, what is argv[2]?

$ ./argv "My School" "is fun"

    ./argv

    fun

    My School

    School

    My School is fun

    NULL

    is

    is fun

    My

---
 Question #3

What is argv?

    An array containing the program compilation flags

    An array containing the program command line arguments

    An array of size argc

---
 Question #4

In the following command, what is argv[2]?

$ ./argv My School is fun

    ./argv

    fun

    My School

    School

    My School is fun

    NULL

    is

    is fun

    My

---
 Question #5

What is argv[0]

    The program name

    NULL

    It does not always exist

    The first command line argument
---
 Question #6

In the following command, what is argv[2]?

$ ./argv "My School is fun"

    ./argv

    fun

    My School

    School

    My School is fun

    NULL

    is

    is fun

    My

---
 ## the answer
 |What is `argc?`|What is `argv[argc]`?|In the following command, what is `argv[2]?`|What is `argv`?|In the following command, what is `argv[2]`?|What is `argv[0]`|In the following command, what is `argv[2]`?|
 |---|---|---|---|---|---|---|
 |The number of command line arguments&&The size of the argv array|NULL|is fun|An array containing the program command line arguments&&An array of size argc|School|The program name|NULL|
 


