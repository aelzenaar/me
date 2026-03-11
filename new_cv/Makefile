all: new_cv listofpubs

new_cv:
	lualatex -interaction=nonstopmode new_cv && bibtex published && bibtex preprints && lualatex -interaction=nonstopmode new_cv && lualatex -interaction=nonstopmode new_cv


listofpubs:
	lualatex -interaction=nonstopmode listofpubs && biber listofpubs && lualatex -interaction=nonstopmode listofpubs && lualatex -interaction=nonstopmode listofpubs
