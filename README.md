
<p align="center">
  <a href="https://www.linkedin.com/in/prafaelramalho/">
    <img alt="Paulo Rafael Ramalho" src="https://img.shields.io/badge/-Paulo Rafael-682998?style=flat&logo=Linkedin&logoColor=white" />
  </a>

  <a aria-label="Completed" href="https://www.42sp.org.br/">
    <img src="https://img.shields.io/badge/42.sp-Libft-682998?logo="></img>
  </a>
</p>

<p align="center">
  115/100
</p>

---

# 🔖 Index

* [What is Libft?](#sparkles-what-is-libft)
* [List of Functions](#bookmark_tabs-list-of-functions)
* [Technologies](#computer-technologies)

---

# :sparkles: What is Libft?

Libft is an individual project at 42 that requires us to re-create some standard C library functions including some additional ones that can be used later to build a library of useful functions for the rest of the program.

At 42 we're not allowed to use some standard libraries on our projects, so we have to keep growing this library with our own functions as we go farther in the program.

---

# :bookmark_tabs: List of Functions

## Functions from `<ctype.h>`

- [x] [`ft_isalpha`](src/ft_isalpha.c)	- checks for an alphabetic character.
- [x] [`ft_isdigit`](src/ft_isdigit.c)	- check for a digit (0 through 9).
- [x] [`ft_isalnum`](src/ft_isalnum.c)	- checks for an alphanumeric character.
- [x] [`ft_isascii`](src/ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [x] [`ft_isprint`](src/ft_isprint.c)	- checks for any printable character.
- [x] [`ft_toupper`](src/ft_toupper.c)	- convert char to uppercase.
- [x] [`ft_tolower`](src/ft_tolower.c)	- convert char to lowercase.

## Functions from `<string.h>`

- [x] [`ft_strlen`](src/ft_strlen.c)	- calculate the length of a string.
- [x] [`ft_memset`](src/ft_memset.c)	- fill memory with a constant byte.
- [x] [`ft_bzero`](src/ft_bzero.c)	- zero a byte string.
- [x] [`ft_memcpy`](src/ft_memcpy.c)	- copy memory area.
- [x] [`ft_memmove`](src/ft_memmove.c)	- copy memory area.
- [x] [`ft_strlcpy`](src/ft_strlcpy.c)	- copy string to a specific size.
- [x] [`ft_strlcat`](src/ft_strlcat.c)	- concatenate a string to a specific size.
- [x] [`ft_strchr`](src/ft_strchr.c)	- locate character in a string.
- [x] [`ft_strrchr`](src/ft_strrchr.c)	- locate character in a string.
- [x] [`ft_strncmp`](src/ft_strncmp.c)	- compare two strings.
- [x] [`ft_memchr`](src/ft_memchr.c)	- scan memory for a character.
- [x] [`ft_memcmp`](src/ft_memcmp.c)	- compare memory areas.
- [x] [`ft_strnstr`](src/ft_strnstr.c)	- locate a substring in a string.
- [x] [`ft_strdup`](src/ft_strdup.c)	- creates a duplicate for the string passed as a parameter.

## Functions from `<stdlib.h>`
- [x] [`ft_atoi`](src/ft_atoi.c)	- convert a string to an integer.
- [x] [`ft_calloc`](src/ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

## Non-standard functions
- [x] [`ft_substr`](src/ft_substr.c)	- returns a substring from a string.
- [x] [`ft_strjoin`](src/ft_strjoin.c)	- concatenates two strings.
- [x] [`ft_strtrim`](src/ft_strtrim.c)	- trims the beginning and end of a string with a specific set of chars.
- [x] [`ft_split`](src/ft_split.c)	- splits a string using a char as parameter.
- [x] [`ft_itoa`](src/ft_itoa.c)	- converts a number into a string.
- [x] [`ft_strmapi`](src/ft_strmapi.c)	- applies a function to each character of a string.
- [x] [`ft_striteri`](src/ft_striteri.c)	- applies a function to each character of a string.
- [x] [`ft_putchar_fd`](src/ft_putchar_fd.c)	- output a char to a file descriptor.
- [x] [`ft_putstr_fd`](src/ft_putstr_fd.c)	- output a string to a file descriptor.
- [x] [`ft_putendl_fd`](src/ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [x] [`ft_putnbr_fd`](src/ft_putnbr_fd.c)	- output a number to a file descriptor.

## Linked list functions

- [x] [`ft_lstnew`](src/ft_lstnew.c)	- creates a new list element.
- [x] [`ft_lstadd_front`](src/ft_lstadd_front.c)	- adds an element at the beginning of a list.
- [x] [`ft_lstsize`](src/ft_lstsize.c)	- counts the number of elements in a list.
- [x] [`ft_lstlast`](src/ft_lstlast.c)	- returns the last element of the list.
- [x] [`ft_lstadd_back`](src/ft_lstadd_back.c)	- adds an element at the end of a list.
- [x] [`ft_lstclear`](src/ft_lstclear.c)	- deletes and free list.
- [x] [`ft_lstiter`](src/ft_lstiter.c)	- applies a function to each element of a list.
- [x] [`ft_lstmap`](src/ft_lstmap.c)	- applies a function to each element of a list.

---

# :computer: Technologies

This Project was made with:

* [C](https://devdocs.io/)
* [Makefile](https://www.gnu.org/software/make/manual/make.html)
* [Shell](https://unixguide.readthedocs.io/en/latest/unixcheatsheet/)
* [clang](https://clang.llvm.org/)

---
