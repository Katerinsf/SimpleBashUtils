CC = gcc
FLAGS = -Wall -Werror -Wextra -std=c11

all: s21_cat

s21_cat:  
	$(CC) $(FLAGS) s21_cat.c -o s21_cat

clean:
	rm -rf s21_cat

style:
	python ../../materials/linters/cpplint.py *.c

test: s21_cat
	chmod +x cat_tests.sh
	./cat_tests.sh
