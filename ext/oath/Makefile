CC      = gcc
RM      = rm -rf 
CFLAGS  = -fPIC
SRCS         := $(wildcard ./*.c)
OBJS         := $(SRCS:.c=.o)  

all : build

build : $(SRCS)
	$(CC) -c $(CFLAGS) $(SRCS) 

clean :
	$(RM) $(OBJS)
