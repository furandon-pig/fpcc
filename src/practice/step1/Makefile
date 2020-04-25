CC=clang
CFLAGS=-std=c11 -g -static

fpcc: step1.c
	$(CC) $(CFLAGS) -o fpcc step1.c

test: fpcc
	./test.sh

clean:
	rm -f fpcc *.o *~ tmp*

.PHONY: test clean

