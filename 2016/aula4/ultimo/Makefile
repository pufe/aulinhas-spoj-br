file=ultimo
test: debug
	./$(file).exe < input | diff - output
debug:
	g++ $(file).cpp -o $(file).exe -g -ansi -pedantic -Wall -Wno-long-long
