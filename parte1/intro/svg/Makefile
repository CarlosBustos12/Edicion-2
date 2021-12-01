.SUFFIXES:
.SUFFIXES: .svg  


# Colores
BL       := $(shell tput -Txterm setaf 0)
RE       := $(shell tput -Txterm setaf 1)
GE       := $(shell tput -Txterm setaf 2)
YE       := $(shell tput -Txterm setaf 3)
LP       := $(shell tput -Txterm setaf 4)
PU       := $(shell tput -Txterm setaf 5)
BL       := $(shell tput -Txterm setaf 6)
WH       := $(shell tput -Txterm setaf 7)

CL := $(shell tput -Txterm sgr0)



a_pdf = $(patsubst %.svg,../pdf/%.pdf,$(wildcard *.svg))


.PHONY: clean

todo: $(a_pdf)


../pdf/%.pdf: %.svg
	@echo "---- Generando ${RE}$@${CL} a partir ${GE}$<${CL} ----"
	@[ -d ../pdf ] || mkdir -v ../pdf 
	@inkscape --export-area-drawing --export-pdf-version=1.5 -o $@ $< 2> /dev/null

clean:
	@echo  Borrando: $(a_pdf)
	- rm -rf $(a_pdf) 

