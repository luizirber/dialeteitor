# Este Makefile não gera o plugin, apenas o programa de teste.
# Para gerar o plugin, leia o arquivo INSTALL!
CC = gcc -g

FLAGS = `pkg-config glib-2.0 --cflags`

LIBS = `pkg-config glib-2.0 --libs`

g_str: g_str.c
	$(CC) g_str.c -o g_str $(FLAGS) $(LIBS)

clean:
	rm g_str
