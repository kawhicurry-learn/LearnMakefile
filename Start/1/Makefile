objects = main.o kdb.o commnd.o display.o \
	insert.o search.o files.o utils.o


edit: $(objects)
	gcc -o edit $(objects)

main.o: mian.c defs.h
	gcc -c main.c

kbd.o: kbdc def.h command.h
	gcc -c kbd.c

command.o: command.c defs.h command.h
	gcc -c command.c

display.o: display.c defs.h buffer.h
	gcc -c display.c

insert.o: insert.c defs.h buffer.h
	gcc -c insert.c

search.o: search.c defs.h buffer.h
	gcc -c search.c

files.o: files.c defs.h buffer.h command.h
	gcc -c files.c

utils.o: utils.c defs.h
	gcc -c utils.c

clean:
	rm edit main.o kdb.o command.o display.o \
	insert.o search.o files.o utils.o