CC=g++
OBJDEPS = helloworld.o cBob.o cCindy.o

all: hellobobandcindy

hellobobandcindy: $(OBJDEPS)
	$(CC) -o hellobobandcindy $(OBJDEPS)

helloworld.o: helloworld.cpp
	$(CC) -c helloworld.cpp

cBob.o: cBob.cpp cBob.h
	$(CC) -c cBob.cpp

cCindy.o: cCindy.cpp cCindy.h
	$(CC) -c cCindy.cpp

clean:
	rm *.o hellobobandcindy