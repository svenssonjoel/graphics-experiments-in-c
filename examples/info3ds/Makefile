C99 = gcc -std=c99 

LIBS = -lGL -lGLU -lglut -lGLEW -l3ds -lpng -lm
CFLAGS = -Wall

INC = -I../../
GFX = ../../graphlib/graphlib.o

all: info3ds

info3ds: info3ds.c 
	$(C99) $(CFLAGS) -o info3ds info3ds.c $(INC) $(GFX) $(LIBS) 


clean: 
	rm info3ds