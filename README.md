# Subject
[libft.en.subject.pdf](https://github.com/mtoof/libft/files/11303482/libft.en.subject.pdf)

# libft
This project was my first project at Hive Helsinki (42 school).
I had to redo a set of functions from the libc. My functions have the
same prototypes and implemented the same behaviors as the originals.

# Part 1 - Libc functions

| function names | function names |
|:--------------:|:--------------:|
|isdigit         | isalpha        |
|isalnum         | isascii        |
|isprint         | strlen         |
|memset          | bzero          |
|memcpy          | memmove        |
|strlcpy         | strlcat        |
|toupper         | tolower        |
|strchr          | strrchr        |
| strrchr|strncmp|
| memchr| memcmp|
|strnstr| atoi|
|calloc|strdup|

# Part 2 - Additional functions

**For more information and know about the prototypes read the subject**
| function names | function names |
|:--------------:|:--------------:|
| ft_substr| ft_strjoin|
|ft_strtrim|ft_split|
|ft_itoa|ft_strmapi|
|ft_striteri| ft_putchar_fd|
|ft_putstr_fd|ft_putendl_fd|
|ft_putnbr_fd||

# Bonus part
| function names | function names |
|:--------------:|:--------------:|
|ft_lstnew|ft_lstadd_front|
|ft_lstsize|ft_lstlast|
|ft_lstadd_back|ft_lstdelone|
|ft_lstclear|ft_lstiter|
|ft_lstmap||

# How does it work?
The goal is to create a library called libftprintf.a from the source files so I can later use that library for other projects at 42.
To create that library, after downloading/cloning this project, cd into the project and call **make** to compile part1 and part2 or **make bonus** for compiling bonus part:
```
git clone git@github.com:mtoof/libft.git
cd libft
make
```
To delete obj files call **make clean** and to delete all obj files and the libft.a library call **make fclean**
