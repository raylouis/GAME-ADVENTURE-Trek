#  Port by Bryan Whitehead <driver@technologist.com>
# send ?'s or bugs to me. This Makefile was tested and
# designed for EMX/GCC/GNUMAKE You will need GNU Utilities
# to run the clean part.

CC = gcc
CFLAGS=-O 

SRCS = abandon.c attack.c autover.c capture.c check_out.c checkcond.c \
        compkl.c computer.c damage.c damaged.c dcrept.c destruct.c \
        dock.c dumpgame.c dumpme.c dumpssradio.c events.c externs.c \
        getcodi.c getpar.c help.c impulse.c initquad.c kill.c klmove.c \
        lose.c lrscan.c main.c move.c nova.c out.c phaser.c play.c ram.c \
        ranf.c rest.c schedule.c score.c setup.c setwarp.c \
        shield.c snova.c srscan.c systemname.c torped.c utility.c \
        visual.c warp.c win.c cgetc.c
OBJS = abandon.o attack.o autover.o capture.o check_out.o checkcond.o \
        compkl.o computer.o damage.o damaged.o dcrept.o destruct.o \
        dock.o dumpgame.o dumpme.o dumpssradio.o events.o externs.o \
        getcodi.o getpar.o help.o impulse.o initquad.o kill.o klmove.o \
        lose.o lrscan.o main.o move.o nova.o out.o phaser.o play.o ram.o \
        ranf.o rest.o schedule.o score.o setup.o setwarp.o \
        shield.o snova.o srscan.o systemname.o torped.o utility.o \
        visual.o warp.o win.o cgetc.o

LDFLAGS = -lm

default: trek.exe

clean:
	rm *.o trek.exe

trek.exe: $(OBJS)
	$(CC) -o $@ $(OBJS) $(LDFLAGS)
