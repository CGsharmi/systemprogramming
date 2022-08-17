CC = g++

CCFLAGS = -c -g -Wall
LDFLAGS = -o 
IFLAGS = -I

INC = inc
BIN = bin
OBJ = obj
SRC = src

all: sysp1 sysPrg2 sysPrg1 sysPrg3 p5

sysp1: $(OBJ)/sysp1.o
	$(CC) $(LDFLAGS) $(BIN)/sysp1 $(OBJ)/sysp1.o

$(OBJ)/sysp1.o: $(SRC)/sysp1.cpp
	$(CC) $(CCFLAGS) $(IFLAGS) $(INC)/ $(SRC)/sysp1.cpp
	mv *.o $(OBJ)/

sysPrg2: $(OBJ)/sysPrg2.o
	$(CC) $(LDFLAGS) $(BIN)/sysPrg2 $(OBJ)/sysPrg2.o

$(OBJ)/sysPrg2.o: $(SRC)/sysPrg2.cpp
	$(CC) $(CCFLAGS) $(IFLAGS) $(INC)/ $(SRC)/sysPrg2.cpp
	mv *.o $(OBJ)/
sysPrg1: $(OBJ)/sysPrg1.o
	$(CC) $(LDFLAGS) $(BIN)/sysPrg1 $(OBJ)/sysPrg1.o

$(OBJ)/sysPrg1.o: $(SRC)/sysPrg1.cpp
	$(CC) $(CCFLAGS) $(IFLAGS) $(INC)/ $(SRC)/sysPrg1.cpp
	mv *.o $(OBJ)/

sysPrg3: $(OBJ)/sysPrg3.o
	$(CC) $(LDFLAGS) $(BIN)/sysPrg3 $(OBJ)/sysPrg3.o

$(OBJ)/sysPrg3.o: $(SRC)/sysPrg3.cpp
	$(CC) $(CCFLAGS) $(IFLAGS) $(INC)/ $(SRC)/sysPrg3.cpp
	mv *.o $(OBJ)/

p5: $(OBJ)/p5.o
	$(CC) $(LDFLAGS) $(BIN)/p5 $(OBJ)/p5.o

$(OBJ)/p5.o: $(SRC)/p5.cpp
	$(CC) $(CCFLAGS) $(IFLAGS) $(INC)/ $(SRC)/p5.cpp
	mv *.o $(OBJ)/

clean:
	rm -f a.out *.o
	rm $(OBJ)/*.o
	rm $(BIN)/sysp1 $(BIN)/sysPrg2 $(BIN)/sysPrg1 $(BIN)/sysPrg3
	rm $(BIN)/p5
	@echo "Cleaning Done!"
