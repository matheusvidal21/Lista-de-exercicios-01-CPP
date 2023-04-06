PROG = questao5
CC = g++
CPPFLAGS = -O0 -g -W -Wall -pedantic
OBJS = questao5.cpp fatorial.cpp primalidade.cpp maiorPrimo.cpp

$(PROG) : $(OBJS)
	$(CC) $(OBJS) -o $(PROG)

questao5.cpp : 
	$(CC) $(CPPFLAGS) -c questao5.cpp //comando quando colocar make questao5.cpp

fatorial.cpp : fatorial.h //puxa o cabeçalho
	$(CC) $(CPPFLAGS) -c fatorial.cpp

primalidade.cpp : primalidade.h
	$(CC) $(CPPFLAGS) -c primalidade.cpp

maiorPrimo.cpp : maiorPrimo.h
	$(CC) $(CPPFLAGS) -c maiorPrimo.cpp

clean:
	rm -f *.o			