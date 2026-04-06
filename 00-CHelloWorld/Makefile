all: hello

hello: hello.c
	gcc -Wall -Wextra -g -std=c23 -pedantic-errors hello.c -o hello

.PHONY=run
run: hello
	./hello
