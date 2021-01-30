MAIN = main.o
FUNCTION = print-function.o

# COMPILAR O FICHEIRO
all: a.out
	./a.out
a.out: $(MAIN) $(FUNCTION)
	gcc -pg $^
# OBTER OS FICHEIROS.O
%.o: %.c
	gcc -c $^
#CLEAN
clean:
	rm *.o
docs:
	doxygen Doxyfile
