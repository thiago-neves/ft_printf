# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: tneves <tneves@student.42sp.org.br>        +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2021/02/09 20:42:53 by tneves            #+#    #+#              #
#    Updated: 2021/02/09 20:42:56 by tneves           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC = ft_memset.c ft_bzero.c ft_memcpy.c ft_memccpy.c ft_memmove.c \
	  ft_memchr.c ft_memcmp.c ft_strlen.c ft_isalpha.c ft_isdigit.c \
	  ft_isalnum.c ft_isascii.c ft_isprint.c ft_toupper.c ft_tolower.c \
	  ft_strchr.c ft_strrchr.c ft_strncmp.c ft_strlcpy.c ft_strlcat.c \
	  ft_strnstr.c ft_atoi.c ft_calloc.c ft_strdup.c \
	  ft_substr.c ft_strjoin.c ft_strtrim.c ft_split.c ft_itoa.c \
	  ft_strmapi.c ft_putchar_fd.c ft_putstr_fd.c ft_putendl_fd.c \
	  ft_putnbr_fd.c \
	  ft_int_to_hex.c ft_maximum.c ft_putchar.c ft_putstr.c \
	  ft_print_multiple_char.c

BONUS_SRC = ft_lstnew.c ft_lstadd_front.c ft_lstsize.c ft_lstlast.c \
			ft_lstadd_back.c ft_lstdelone.c ft_lstclear.c ft_lstiter.c \
			ft_lstmap.c

OBJ = ft_memset.o ft_bzero.o ft_memcpy.o ft_memccpy.o ft_memmove.o \
	  ft_memchr.o ft_memcmp.o ft_strlen.o ft_isalpha.o ft_isdigit.o \
	  ft_isalnum.o ft_isascii.o ft_isprint.o ft_toupper.o ft_tolower.o \
	  ft_strchr.o ft_strrchr.o ft_strncmp.o ft_strlcpy.o ft_strlcat.o \
	  ft_strnstr.o ft_atoi.o ft_calloc.o ft_strdup.o \
	  ft_substr.o ft_strjoin.o ft_strtrim.o ft_split.o ft_itoa.o \
	  ft_strmapi.o ft_putchar_fd.o ft_putstr_fd.o ft_putendl_fd.o \
	  ft_putnbr_fd.o \
	  ft_int_to_hex.o ft_maximum.o ft_putchar.o ft_putstr.o \
	  ft_print_multiple_char.o

BONUS_OBJ = ft_lstnew.o ft_lstadd_front.o ft_lstsize.o ft_lstlast.o \
			ft_lstadd_back.o ft_lstdelone.o ft_lstclear.o ft_lstiter.o \
			ft_lstmap.o

all: $(NAME)

$(NAME): $(SRC)
	@gcc -Wall -Wextra -Werror -c $(SRC)
	@ar rc $(NAME) $(OBJ)
	@ranlib $(NAME)

bonus: $(SRC) $(BONUS_SRC)
	@gcc -Wall -Wextra -Werror -c $(SRC) $(BONUS_SRC)
	@ar rc $(NAME) $(OBJ) $(BONUS_OBJ)
	@ranlib $(NAME)

clean:
	@/bin/rm -f $(OBJ) $(BONUS_OBJ)

fclean: clean
	@/bin/rm -f $(NAME)

re: fclean all

.PHONY: clean fclean
