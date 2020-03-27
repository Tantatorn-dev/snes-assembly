main.smc: main.o
	ld65 -C memmap.cfg main.o -o main.smc

main.o: main.s
	ca65 --cpu 65816 -o main.o main.s

clean:
	rm main.o main.smc