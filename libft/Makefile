# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: oyenyi- <marvin@42.fr>                     +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/05/25 13:55:29 by oyenyi-           #+#    #+#              #
#    Updated: 2018/06/06 22:50:08 by oyenyi-          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #


NAME = libft.a

SRC = ft_strlen.c ft_strcpy.c ft_strncpy.c ft_isalpha.c ft_isdigit.c ft_isascii.c\
	  ft_isalnum.c ft_isprint.c ft_isspace.c ft_islower.c ft_isupper.c ft_strdup.c\
	  ft_strcat.c ft_strlcat.c ft_strncat.c ft_tolower.c ft_toupper.c ft_strchr.c\
	  ft_strrchr.c ft_strstr.c ft_strnstr.c ft_strcmp.c ft_strncmp.c ft_atoi.c\
	  ft_bzero.c ft_memcpy.c ft_memccpy.c ft_memmove.c ft_memchr.c ft_memcmp.c\
	  ft_memset.c ft_putchar.c ft_putchar_fd.c ft_memalloc.c ft_memdel.c ft_itoa.c\
	  ft_strnew.c ft_strdel.c ft_strclr.c ft_striter.c ft_striteri.c ft_strmap.c\
	  ft_strmapi.c ft_strequ.c ft_strnequ.c ft_strsub.c ft_strjoin.c ft_strtrim.c\
	  ft_putstr.c ft_putendl.c ft_putendl_fd.c ft_putstr_fd.c ft_putnbr.c\
	  ft_putnbr_fd.c ft_strsplit.c ft_lstnew.c ft_lstdelone.c ft_lstdel.c\
	  ft_lstadd.c ft_lstiter.c ft_lstmap.c\

 OBJS = *.o

FLAGS = -Wall -Wextra -Werror

CC = gcc

HEADER = libft.h

all: $(NAME)

$(NAME):
	$(CC) $(FLAGS) -c $(SRC)
	ar rc $(NAME) $(OBJS)
	ranlib $(NAME)

clean:
	rm -rf $(OBJS)

fclean: clean 
	rm -f $(NAME)

re: fclean all
