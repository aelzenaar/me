all: new_cv new_cv_short listofpubs

new_cv:
	lualatex -interaction=nonstopmode new_cv
	bibtex published
	bibtex preprints
	lualatex -interaction=nonstopmode new_cv
	lualatex -interaction=nonstopmode new_cv

new_cv_short:
	lualatex -interaction=nonstopmode new_cv_short
	lualatex -interaction=nonstopmode new_cv_short

listofpubs:
	lualatex -interaction=nonstopmode listofpubs
	bibtex published
	bibtex preprints
	lualatex -interaction=nonstopmode listofpubs
	lualatex -interaction=nonstopmode listofpubs
