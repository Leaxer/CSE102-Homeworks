all: clean compile run

compile: main.c util.c util.h
	@gcc -o test main.c util.c

run:
	./test

clean:
	@rm -f *.o
	@rm -f *.txt
	@rm -f test
