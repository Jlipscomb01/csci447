
OBJS = CPPModul.o CPPModulWrapper.o initmodul.o

cppmod: $(OBJS)
	g++ -lpython $(OBJS) -fpic -shared -o CPPModul.so

%.o: %.cpp
	g++ -I/usr/include/python2.7 -fpic -c $<
