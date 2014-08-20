all: 
	gcc -o test.out test.o test2.o
	
test.o: test.c
	gcc -c test.c
	
test2.o: test2.c test2.h
	gcc -c test2.c
	
clean:
	rm -rf test.o
	rm -rf test2.o 
	rm -rf test.out
	
	
