##
## EPITECH PROJECT, 2019
## MAKEFILE
## File description:
## Makefile for synthesis pool
##
SRC =	./calc.c	\
	./main.c	\

NAME =fakeProj

OBJ = $(SRC:.c=.o)

CFLAGS = -g3 -Iinclude -Wall -Wextra

all : $(NAME)

$(NAME):	$(OBJ)
	gcc $(CFLAGS) -o $(NAME) $(OBJ)

clean :
	rm -f $(OBJ)

fclean : clean
	rm -f $(NAME)

re:			fclean all

.PHONY:		all clean fclean re
