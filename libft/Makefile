# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: lcrawn <marvin@42.fr>                      +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/04/06 12:22:56 by lcrawn            #+#    #+#              #
#    Updated: 2019/08/30 19:44:23 by lcrawn           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SRC = ft_list_reverse.c ft_memset.c ft_bzero.c ft_memcpy.c ft_memccpy.c ft_memmove.c ft_memcmp.c \
	  ft_list_push_back.c ft_strlen.c ft_strncpy.c ft_strcat.c ft_strncat.c \
	  ft_list_find.c ft_strlcat.c ft_strchr.c ft_strrchr.c ft_strstr.c ft_strnstr.c ft_strcmp.c \
	  ft_strrev.c ft_strncmp.c ft_atoi.c ft_isalpha.c ft_isdigit.c ft_isalnum.c ft_isascii.c \
	  ft_list_foreach_if.c ft_isprint.c ft_toupper.c ft_tolower.c ft_memalloc.c ft_memdel.c \
	  ft_strclr.c ft_striter.c ft_striteri.c ft_strmap.c ft_strmapi.c ft_memchr.c \
	  ft_strequ.c ft_strnequ.c ft_strsub.c ft_strjoin.c ft_strtrim.c ft_strsplit.c \
	  ft_itoa.c ft_putendl.c ft_putchar_fd.c \
	  ft_putstr_fd.c ft_putendl_fd.c ft_putnbr_fd.c ft_lstnew.c ft_lstdelone.c \
	  ft_lstdel.c ft_lstadd.c ft_lstiter.c ft_lstmap.c

SRC_O = $(SRC:.c=.o)

NAME = libft.a

HDR = libft.h

all: $(NAME)

$(NAME): $(SRC_O)
		gcc -Wall -Wextra -Werror -c $(SRC)
		ar rc $(NAME) $(SRC_O)

clean:
		rm -f $(SRC_O)

fclean: clean
		rm -f $(NAME)

re: fclean all
