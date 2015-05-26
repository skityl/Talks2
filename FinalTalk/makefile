READ = evince
COMP = pdflatex
NAME = talk

$(NAME).pdf: $(NAME).tex
	$(COMP) $<
	$(COMP) $<

read: $(NAME).pdf
	$(READ) $<

clean:
	rm -f *.log *.aux *~ *.toc *.snm *.nav *.out

tea:
	@echo "Make it yourself."    
