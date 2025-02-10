<p align="center">
   This project is about coding a C library.<br>
   It will contain a lot of general purpose functions your programs will rely upon.
</p>

#  Project

This is the first project of the common core at 42 São Paulo. The project wants that you recode some functions from **C Library** and other useful functions that you could use in your future projects.

## Menu

1. [How to use it?](#how-to-use-it)
   - [Mandatory](#mandatory)
   - [Bonus](#bonus)
   - [Remove](#remove)
   - [Declare](#declare)

## How to use it?

Clone the repository to your project directory:

```shell
git clone https://github.com/victorcploureiro/libft_project.git libft
```

#### Mandatory:

Then use the command `make` inside the _libft_ directory to build the compiled _libft archive_ of the mandatory part of the project.

#### Bonus:

If you need the bonus part, use the command `make bonus` to include the bonus functions in the _libft archive_.

#### Remove:

To remove the objects compiled, use the command `make clean`.

#### Delete:

And, if you want to delete everything, use the command `make fclean`.

#### Declare:
To use the functions of the library you need to _include_ it in your project and compile your project with the _libft archive_.

```c
#include "libft.h"
```

```shell
gcc main.c -I ./libft ./libft/libft.a
```

---
