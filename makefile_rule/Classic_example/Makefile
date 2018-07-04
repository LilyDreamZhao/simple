all:main.o add.o
	gcc main.o add.o -o all
main.o:main.c add.o
	gcc -c main.c -o main.o
add.o:add.c
	gcc -c add.c -o add.o
.PHONY:clean 
clean:
	-rm -f *.o
