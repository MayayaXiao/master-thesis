LATEXMK := $(shell latexmk -v 2>/dev/null)

# Include Makefile depending wheter latemk available or not 
ifdef LATEXMK
include makefiles/Makefile.latexmk
else
include makefiles/Makefile.legacy
endif
