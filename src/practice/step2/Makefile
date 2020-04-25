CC=clang
CFLAGS=-std=c11 -g -static

SRC=step2.c

fpcc: $(SRC)
	$(CC) $(CFLAGS) -o fpcc $(SRC)

test: fpcc
	./test.sh

clean:
	rm -f fpcc *.o *~ tmp*

.PHONY: test clean

