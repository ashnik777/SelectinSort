start:main.o printArray.o selectionSort.o 
	g++ $^ -o ../bin/$@
%.o:%.cpp
	g++ -c $^ -o $@
clean:
	rm *.o
