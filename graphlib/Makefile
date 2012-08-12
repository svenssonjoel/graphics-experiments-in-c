
C99 = gcc -std=c99 
##-lglut -lGLEW -lGLU -lm -l3ds
LIBS = 
CFLAGS = -Wall

SRCS=$(wildcard *.c)
OBJS=$(SRCS:.c=.o)

## $(LIBS)
%.o:%.c
	$(C99) -c -o $@ $^ $(CFLAGS) 


all: graphlib.o


graphlib.o: $(OBJS)
	ld -r $(OBJS) -o graphlib.o

clean: 
	rm *.o