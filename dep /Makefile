prog: main_dep.o dep.o
	gcc main_dep.o dep.o  -lSDL -lSDL_image -lSDL_mixer -lSDL_ttf -o prog -g
mainn.o:mainn.c
	gcc -c main_dep.c -g
ennemi.o:dep.c
	gcc -c dep.c -g
