CC=g++
CFLAGS=-std=c++11
OUTPUTNAME=Calc

all: Stack Calc
	g++ -std=c++11 Stack.o Calc.o -o $(OUTPUTNAME)

Stack: Stack.cpp
	$(CC) $(CFLAGS) -c Stack.cpp

Calc: Calc.cpp
	$(CC) $(CFLAGS) -c Calc.cpp

clean:
	rm *.o
	rm $(OUTPUTNAME)
