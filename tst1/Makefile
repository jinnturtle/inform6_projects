NAME = main
OUTP = main.ulx
SRC = main.inf
LIB_DIR = ${HOME}/.local/share/inform/lib

all: $(OUTP)

%.ulx: %.inf
	inform -G +$(LIB_DIR) $(SRC) $(OUTP)

clean:
	@rm -rv $(OUTP)
