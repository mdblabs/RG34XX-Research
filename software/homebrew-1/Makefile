CC = gcc
CFLAGS = -Wall -Wextra -std=c11
LIBS = `sdl2-config --cflags --libs` -lSDL2_ttf
SRC = main.c
OUT = homebrew-1

all:
	$(CC) $(CFLAGS) $(SRC) -o $(OUT) $(LIBS)

clean:
	rm -f $(OUT)
