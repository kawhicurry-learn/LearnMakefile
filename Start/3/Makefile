objects = main.o kdb.o commnd.o display.o \
	insert.o search.o files.o utils.o


edit: $(objects)
	gcc -o edit $(objects)

$(objects): defs.h
kbd.o command.o files.o:commnd.h
display.o insert.o files.o:buffer.h

.PHONY:clean
clean:
	-rm edit $(objects)