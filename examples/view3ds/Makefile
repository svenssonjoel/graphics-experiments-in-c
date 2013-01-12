C99 = gcc -std=c99 

LIBS = -lGL -lGLU -lGLEW -lglut -l3ds -lpng -lm
CFLAGS = -Wall

INC = -I../../
GFX = ../../graphlib/graphlib.o

all: view3ds

view3ds: view3ds.c 
	$(C99) $(CFLAGS) -o view3ds view3ds.c $(INC) $(GFX)  $(LIBS)


clean: 
	rm view3ds	
