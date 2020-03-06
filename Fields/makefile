# If you want to use this on your own machine, change CLASSDIR and/or INCLUDE and LIBS so
# that they point to the correct directories/library.

# CLASSDIR = $(HOME)
CLASSDIR = /Desktop/Fields

EX = printwords
all: $(EX) 
clean: 
	rm -f $(EX) *.o

printwords: printwords.o
	gcc -o printwords printwords.o libfdr.a

.SUFFIXES: .c .o
