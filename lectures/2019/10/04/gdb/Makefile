CXX = g++
# -ggdb compiler option creates a gdb friendly binary that will givbree us more information during debugging!
FLAGS = -ggdb -Wall -std=c++11 

main: main.cc # Fun Fact g++ recognizes .cc, .cpp, .cxx, .C, .CPP, .cp, c++ has valid c++ files :)
	${CXX} ${FLAGS} -o main.out main.cc

clean:
	rm -f main