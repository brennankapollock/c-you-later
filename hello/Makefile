all: hello

hello: hello.o
	gcc -Wall -std=c99 -o output_binary hello.o

hello.o: hello.c
	gcc -Wall -std=c99 -c hello.c

.PHONY: clean

clean:
	rm -f output_binary hello.o