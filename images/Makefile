GRAPHS = pf_pfasst_t.gv pfasst_dependencies.gv

all: $(GRAPHS:.gv=.pdf)

%.pdf: %.gv
	dot -Tpdf -o $@ $<
