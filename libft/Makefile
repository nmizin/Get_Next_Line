# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: nmizin <marvin@42.fr>                      +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/02/05 19:04:30 by nmizin            #+#    #+#              #
#    Updated: 2018/02/05 19:04:34 by nmizin           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
INCLUDES = includes
CC = gcc -Wall -Wextra -Werror
SRCS = ft_atoi.c ft_bzero.c ft_isalnum.c ft_isalpha.c ft_isascii.c ft_isdigit.c ft_isprint.c ft_itoa.c\
ft_lstadd.c ft_lstdel.c ft_lstdelone.c ft_lstiter.c ft_lstmap.c ft_lstnew.c ft_memalloc.c ft_memccpy.c\
ft_memchr.c ft_memcmp.c ft_memcpy.c ft_memdel.c ft_memmove.c ft_memset.c ft_putchar.c ft_putchar_fd.c\
ft_putendll.c ft_putendl_fd.c ft_putnbr.c ft_putnbr_fd.c ft_putstr.c ft_putstr_fd.c ft_strcat.c\
ft_strchr.c ft_strclr.c ft_strcmp.c ft_strcpy.c ft_strdel.c ft_strdup.c ft_strequ.c ft_striter.c\
ft_striteri.c ft_strjoin.c ft_strlcat.c ft_strlen.c ft_strmap.c ft_strmapi.c ft_strncat.c ft_strncmp.c\
ft_strncpy.c ft_strnequ.c ft_strnew.c ft_strnstr.c ft_strrchr.c ft_strsplit.c ft_strstr.c ft_strsub.c\
ft_strtrim.c ft_tolower.c ft_toupper.c my_ft_lettercount.c  my_ft_setyourchar.c my_ft_strcomp.c\
my_ft_strim.c my_ft_strrev.c my_ft_wordcount.c my_ft_wordcrt.c ft_atoi_base.c ft_itoa_base.c


all: $(NAME)

%.o:%.c
	$(CC) -I $(INCLUDES) -c $^

$(NAME): *.o
	@ar rc $(NAME) *.o
	@ranlib $(NAME)

clean:
	@/bin/rm -rf *.o *.out

fclean: clean
	@/bin/rm -rf $(NAME)

re: fclean all

