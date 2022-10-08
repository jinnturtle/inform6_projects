NAME = story
OUTP = $(NAME).ulx
SRC = main.inf
LIB_DIR = ${HOME}/.local/share/inform/lib
INFORM6 = inform6
INFORM6_ARGS = -Gx

all: $(OUTP)

$(OUTP): $(SRC)
	$(INFORM6) $(INFORM6_ARGS) +$(LIB_DIR) $< $@

clean:
	@rm -rv $(OUTP)
