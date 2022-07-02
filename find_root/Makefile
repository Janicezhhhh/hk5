all:	./src/roots.c
	g++ -o ./bin/roots ./src/roots.c -lgsl -lgslcblas
debug:	./src/roots.c
	g++ -o ./bin/roots ./src/roots.c -lgsl -lgslcblas
report:	./doc/report.tex
	xelatex ./doc/report.tex
clean:
	rm  *.aux *.log
