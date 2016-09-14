Target = amrnb-dec
Objects = amrnb-dec.o

CC = arm-linux-gcc
Compile = $(CC)
Link = $(CC) -lstdc++

LIB = -Wall -lz -lrt -lpthread \
	-L./ -lopencore-amrnb 

main :  $(Objects)    
	$(Link) $(Objects) $(LIB) -o $(Target)


.cpp.o :
	$(Compile) -c -o $@ $< $(INCLUDE)
.c.o :
	$(Compile) -c -o $@ $< $(INCLUDE)	
clean:
	rm *.o

#	rm $(Target)

