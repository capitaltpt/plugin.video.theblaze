CC=gcc
CFLAGS=-O2
LIBS=-lm -lcurl -lcrypto -lconfig -lpthread

mlb = mlb

all: mlb

mlb:
	 $(CC) $(CFLAGS) mlb.c utils.c output.c -g $(LIBS) -o mlbhls

clean:
	rm -f *.o mlbhls

