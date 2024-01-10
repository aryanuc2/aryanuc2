CC=gcc
CFLAGS= -Wall -Werror

.PHONY: build
build: $(PROG)
	mkdir -p build
	$(CC) $(CFLAGS) $(PROG) -o ./build/$(basename $(notdir $(PROG)))

.PHONY: clean
clean: 
	rm -rf ./build