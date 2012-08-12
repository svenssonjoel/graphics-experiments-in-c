C99 = gcc -std=c99 

LIBS = -lglut -lGLEW -lGLU -l3ds -lpng -lm
CFLAGS = -Wall

INC = -I../../
GFX = ../../graphlib/graphlib.o

all: show_feig

show_feig: show_feig.c 
	$(C99) $(CFLAGS) -o show_feig show_feig.c $(GFX) $(INC) $(LIBS) 


clean: 
	rm show_feig