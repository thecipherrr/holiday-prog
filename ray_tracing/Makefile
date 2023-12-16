CC=g++
CFLAGS = -Wall -Wextra -pedantic

all: prog

prog: main.cc
	$(CC) $(CFLAGS) -o prog main.cc

convert:
	prog.exe > image.ppm

clean:
	del *.o &&  del *.exe && del *.ppm
