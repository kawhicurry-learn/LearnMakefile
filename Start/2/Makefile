objects = main.o kdb.o commnd.o display.o \
	insert.o search.o files.o utils.o


edit: $(objects)
	gcc -o edit $(objects)

main.o: defs.h

kbd.o:  def.h command.h

command.o:  defs.h command.h

display.o: defs.h buffer.h

insert.o: defs.h buffer.h

search.o: defs.h buffer.h

files.o: defs.h buffer.h command.h

utils.o: defs.h

clean:
	rm edit main.o kdb.o command.o display.o \
	insert.o search.o files.o utils.o