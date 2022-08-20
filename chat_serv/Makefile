CC:=gcc

TARGET = chat_serv
OBJECT = $(TARGET).o 

LDFLAGS = -D_REENTRANT -pthread

$(TARGET) : $(OBJECT)
	$(CC) -o $@ $^ $(LDFLAGS)
.c.o:
	$(CC) -c -o $@ $<
clean:
	rm -f *.o $(TARGET)
