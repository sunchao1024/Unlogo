# GNU Make solution makefile autogenerated by Premake
# Type "make help" for usage help

ifndef config
  config=debug
endif
export config

PROJECTS := unlogo

.PHONY: all clean help $(PROJECTS)

all: $(PROJECTS)

unlogo: 
	@echo "==== Building unlogo ($(config)) ===="
	@${MAKE} --no-print-directory -C . -f unlogo.make

clean:
	@${MAKE} --no-print-directory -C . -f unlogo.make clean

help:
	@echo "Usage: make [config=name] [target]"
	@echo ""
	@echo "CONFIGURATIONS:"
	@echo "   debug"
	@echo "   release"
	@echo ""
	@echo "TARGETS:"
	@echo "   all (default)"
	@echo "   clean"
	@echo "   unlogo"
	@echo ""
	@echo "For more information, see http://industriousone.com/premake/quick-start"
