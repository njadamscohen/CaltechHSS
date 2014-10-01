%:%.tex
	latexmk -pdf $@.tex && evince $@.pdf & $(MAKE) clean 
clean:
	rm -f *.out *.aux *.fls *.log *.fdv*
