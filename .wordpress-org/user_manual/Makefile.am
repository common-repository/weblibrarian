UMAN = user_manual
UMANIT = user_manual_IT

TEXS = $(UMAN).tex
TEXSIT = $(UMANIT).tex
FIGURES = frontside.png frontone.png EditPatronInfo.png PatronManagement.png \
	  ColectionListing.png AddItem.png AmazonSearch.png \
	  AmazonSearchResults.png AmazonLookupResults.png \
	  CirculationTypesList.png CirculationTypesStatsList.png \
	  MainCirculation.png ItemCirculationRecord.png \
	  PatronCirculationRecord.png CirculationHoldList.png \
	  CirculationCheckoutList.png CirculationCheckinPage.png \
	  FindPatron.png

EXTRA_DIST = $(TEXS) $(FIGURES)

PDF = $(UMAN).pdf
PDFIT = $(UMANIT).pdf

noinst_DATA=$(PDF) $(PDFIT)

$(PDF) : $(TEXS) $(FIGURES)
	$(PDFLATEX) $(UMAN)
	$(PDFLATEX) $(UMAN)
	$(PDFLATEX) $(UMAN)

$(PDFIT) : $(TEXSIT) $(FIGURES)
	$(PDFLATEX) $(UMANIT)
	$(PDFLATEX) $(UMANIT)
	$(PDFLATEX) $(UMANIT)


