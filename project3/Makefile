# makefile for Virtual Memeory Unit (MMU)
#
# usage: make mmu 

CC=gcc
CFLAGS=-Wall

clean:
	rm -rf *.o
	rm -rf mmu
	rm -rf mmu128
	
mmu: 
	$(CC) -std=c99 mmu.c -o mmu
	$(CC) -std=c99 mmu128.c -o mmu128