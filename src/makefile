# Compiler Information
CPP := g++
CPPFLAGS := -std=c++17 -Wall -Wextra -Wpedantic -Werror


# Program Info

PROGRAM := test

SRCS := $(wildcard *.cpp)
OBJS := $(patsubst %.cpp,%.o,$(wildcard *.cpp))


# Project Compilation

$(PROGRAM): $(OBJS)
	$(CPP) $(CPPFLAGS) -o $(PROGRAM) $(OBJS)

$(OBJS): $(SRCS)
	$(CPP) -c $(CPPFLAGS) $(SRCS)

clean:
	rm -rf $(wildcard *.o)
	rm -rf $(wildcard.exe)
