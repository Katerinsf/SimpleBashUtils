CC = gcc
FLAGS = -Wall -Werror -Wextra -std=c11

all:s21_grep

s21_grep:
	$(CC) $(FLAGS) s21_grep.c -o s21_grep

clean:
	rm -rf s21_grep

test: s21_grep
	chmod +x grep_tests.sh
	./grep_tests.sh

style:
	python ../../materials/linters/cpplint.py *c


