main: mypipe.o main.o 
	gcc mypipe.o main.o -o main -lpthread 
	
mypipe.o: mypipe.c mypipe.h
	gcc -Wall -c mypipe.c 

main.o: main.c mypipe.h
	gcc -Wall -c main.c -lpthread
	

