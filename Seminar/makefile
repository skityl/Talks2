READ = evince
COMP = pdflatex
NAME = talk

$(NAME).pdf: $(NAME).tex
	$(COMP) $<

read: $(NAME).pdf
	$(READ) $<

clean:
	rm -f *.log *.aux *~ *.toc *.snm *.nav

tea:
	@echo "Make it yourself."    
