# Monty. Custom Bytecode Interpreter #

<div style="text-align: justify">

Thank you for visiting this repository which contain my work as C language programming developer. 	


![Logo](https://www.google.com/imgres?imgurl=http%3A%2F%2Fimages.squarespace-cdn.com%2Fcontent%2Fv1%2F56f304cc4d088ecd01de4215%2F1458858255270-3HZ0BZ14YVSQ9MZBS6U4%2FMONTY%2B-%2BNAME%2BLOGO%2B-%2B01.png&imgrefurl=http%3A%2F%2Fwww.remyboy1738.com%2Fbio&tbnid=oaeKztc8YcycmM&vet=12ahUKEwiYu--quK_1AhX5rIQIHfpzB7AQMygnegUIARCvAg..i&docid=Zy8DtS25qePhwM&w=1500&h=575&q=monty%20images&ved=2ahUKEwiYu--quK_1AhX5rIQIHfpzB7AQMygnegUIARCvAg)

# Getting Started :running:
<div style="text-align: justify">

## Table of Contents
* [AUTHORS](./AUTHORS)
* [MIT License](./LICENSE)
* [About](#about)
* [Dependences](#dependences)
* [Installing, compiling and using](#installing, compiling and using)
* [Builtins](#builtins)
* [Man page]
* [Credits](#credits)

## About
This directory contains a collection of files, functions, structs and scripts used to build and manage this repository. If there are any issues regarding the intention of a particular script (or even part of a certain script), please reach out to us.
	
	Contents:

What do LIFO and FIFO mean

What is a stack, and when to use it

What is a queue, and when to use it

What are the common implementations of stacks and queues

What are the most common use cases of stacks and queues

What is the proper way to use global variables

	
## Dependences 
	
> [monty.h](https://github.com/Imanolasolo/holbertonschool-low_level_programming/blob/main/0x18-dynamic_libraries/main.h) --> Header file containingall functions involved in project.

> [README.md](https://github.com/Imanolasolo/holbertonschool-low_level_programming/blob/main/0x18-dynamic_libraries/README.md) ---> README file to show the project insights. 

>[errors_A.c](https://github.com/Imanolasolo/holbertonschool-low_level_programming/blob/main/0x18-dynamic_libraries/libdynamic.so) ---> Print different errors

>[errors_B.c](https://github.com/Imanolasolo/holbertonschool-higher_level_programming/blob/master/0x04-python-more_data_structures/2-uniq_add.py) ---> Print different errors.

>[int_2_string.c]() ---> Operations with integers and strings in buffer

>[m_funcs1-c]() ---> Push, pall, pint, pop and swap functions

>[m_funcs2.c]() ---> Add, sub, div, mul and mod functions

>[m_funcs3.c]() ---> Nop, pchar and pstr functions

>[m_funcs4.c]() ---> Rotl, rotr, stack and queue functions

>[main.c]() ---> Main funcyion to execute the program

>[run_monty.c]() ---> Primary function to execute a Monty bytecodes script.

>[set_op-token_error.c]() ---> Sets last element of op_toks to be an error code

>[stack.c]() ---> Functions for stack operations

>[string_tokenizer.c] ---> Tokenizing functions.


## Installing, compiling and using
	
> Only install cloning this repository on your local device:  https://github.com/Imanolasolo/monty.git
	
> Compile the `.c` programs with `gcc -Wall -Werror -Wextra -pedantic -std=c90 *.c -o monty`
	
> Run `./monty` followed by `.m` file


## Builtins
```
void free_stack(stack_t **stack);
int init_stack(stack_t **stack);
int check_mode(stack_t *stack);
void free_tokens(void);
unsigned int token_arr_len(void);
int run_monty(FILE *script_fd);
void set_op_tok_error(int error_code)
void monty_push(stack_t **stack, unsigned int line_number);
void monty_pall(stack_t **stack, unsigned int line_number);
void monty_pint(stack_t **stack, unsigned int line_number);
void monty_pop(stack_t **stack, unsigned int line_number);
void monty_swap(stack_t **stack, unsigned int line_number);
void monty_add(stack_t **stack, unsigned int line_number);
void monty_nop(stack_t **stack, unsigned int line_number);
void monty_sub(stack_t **stack, unsigned int line_number);
void monty_div(stack_t **stack, unsigned int line_number);
void monty_mul(stack_t **stack, unsigned int line_number);
void monty_mod(stack_t **stack, unsigned int line_number);
void monty_pchar(stack_t **stack, unsigned int line_number);
void monty_pstr(stack_t **stack, unsigned int line_number);
void monty_rotl(stack_t **stack, unsigned int line_number);
void monty_rotr(stack_t **stack, unsigned int line_number);
void monty_stack(stack_t **stack, unsigned int line_number);
void monty_queue(stack_t **stack, unsigned int line_number);
char **strtow(char *str, char *delims);
char *get_int(int n);
int usage_error(void);
int malloc_error(void);
int f_open_error(char *filename);
int unknown_op_error(char *opcode, unsigned int line_number);
int no_int_error(unsigned int line_number);
int pop_error(unsigned int line_number);
int pint_error(unsigned int line_number);
int short_stack_error(unsigned int line_number, char *op);
int div_error(unsigned int line_number);
int pchar_error(unsigned int line_number, char *message);

```
		
## Man page

-  No man page

## Flowchart
	
- No flowchart

## Resources

**Read or watch**:

[What is difference between Dynamic and Static library (Static and Dynamic linking)](https://www.youtube.com/watch?v=eW5he5uFBNM])
[Create dynamic libraries on Linux](https://www.google.com/#q=linux+create+dynamic+library)
[Technical Writing](https://students-support.hbtn.io/hc/en-us/articles/360023750254)


## Usage



## Credits

## Author(s):blue_book:

Work is owned and maintained by:
* Imanol Asolo <[3848](mailto:3848@holbertonschool.com)> [![M](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/25px-Octicons-mark-github.svg.png)](https://github.com/Imanolasolo) [![M](https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/25px-Twitter_Bird.svg.png)](https://twitter.com/jjusturi) [![M](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/25px-LinkedIn_logo_initials.png)](https://www.linkedin.com/in/imanol-asolo-5ba9b42a/)


## Acknowledgments :mega: 

### **`Holberton School`** (*providing guidance*)
This program was written as part of the curriculum for Holberton School.
Holberton School is a campus-based full-stack software engineering program
that prepares students for careers in the tech industry using project-based
peer learning. For more information, visit [this link](https://www.holbertonschool.com/).
<p align="center">
	<img src="https://assets.website-files.com/6105315644a26f77912a1ada/610540e8b4cd6969794fe673_Holberton_School_logo-04-04.svg" alt="This is a secret;)">
</p>
