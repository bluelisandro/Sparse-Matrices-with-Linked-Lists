
matrix_gui: main.o Graphics.o Node.o Matrix.o
	g++ *.o -o matrix_gui -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio

main.o: main.cpp
	g++ -c main.cpp

Graphics.o: Graphics.cpp
	g++ -c Graphics.cpp

Node.o: Node.cpp Node.h
	g++ -c Node.cpp

Matrix.o: Matrix.cpp Matrix.h
	g++ -c Matrix.cpp

clean:
	rm *.o matrix_gui