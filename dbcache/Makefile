all:
	gcc -O3 -g -c *.c -I../
	ar -rc dbcache.a *.o
	mv dbcache.a ./frontend
	rm -f *.o
debug:
	gcc -g -c *.c -I../
	ar -rc dbcache.a *.o
	mv dbcache.a ./frontend
	rm -f *.o	
