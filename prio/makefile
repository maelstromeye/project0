all: yoh run clean

yoh: main.o yo.o
	g++ main.o yo.o -o yoh
main.o: main.cpp
	g++ -c main.cpp
to.o: yo.cpp
	g++ -c yo.cpp
clean:
	rm -rf *.o
run:
	./yoh	
