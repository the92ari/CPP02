CC = c++ -std=c++98

FLAGS = -Wall -Wextra -Werror

SRCS = main.cpp Fixed.cpp Point.cpp bsp.cpp

OBJS = $(SRCS:.cpp=.o)

NAME = bsp

all:	$(NAME)

$(NAME):	$(OBJS)
			$(CC) $(FLAGS) $(OBJS) -o $(NAME)

clean:	
		rm -rf $(OBJS)

fclean:	clean
		rm -rf $(NAME)

re:		fclean all