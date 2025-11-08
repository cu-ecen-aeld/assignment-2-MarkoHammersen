CC := $(CROSS_COMPILE)gcc
CFLAGS := -g -Wall -Werror
TARGET := writer

all: $(TARGET)

$(TARGET): writer.c
	$(CC) $(CFLAGS) -o $(TARGET) writer.c

clean:
	rm -f $(TARGET) *.o
