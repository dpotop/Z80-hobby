SOURCES = \
	ascii.asm \
	basic.asm \
	init.asm \
	keywords.asm \
	vectors.asm \
	error.asm \
	io.asm \
	ram.asm \
	print.asm \
	statements.asm \


all: basic.h

basic.h: basic.bin convert.exe
	./convert.exe > basic.h

convert.exe: convert.c
	gcc convert.c -o convert.exe

basic.bin: $(SOURCES)
	z80asm basic.asm -o basic.bin -l 2> basic.lst

clean:
	rm -f basic.bin basic.lst convert.exe prog-bin.h basic.h
