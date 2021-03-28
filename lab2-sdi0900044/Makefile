all:sorting

sorting: PQImplementation.o sorting.o 
	gcc PQImplementation.o sorting.o -o sorting

PQImplementation.o : PQImplementation.c PQInterface.h
		gcc -c PQImplementation.c
sorting.o: sorting.c PQInterface.h
		gcc -c sorting.c

clean:
	rm -rf *o sorting
