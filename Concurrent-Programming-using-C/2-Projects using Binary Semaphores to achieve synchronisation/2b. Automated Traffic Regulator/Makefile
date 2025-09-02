all:
	gcc -g -Wall -o semlib.o -c semlib.c
	gcc -g -Wall -o main main.c semlib.o -lpthread

clean:
	$(RM) main
	$(RM) semlib.o
	$(RM) out.txt
