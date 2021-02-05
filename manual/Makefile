srcdir = .

DAMELIBRARIES = ${srcdir}/damelibraries.texi
DAMELIBRARIES_ES = ${srcdir}/damelibraries.es.texi
DAMELIBRARIES_PO = ${srcdir}/damelibraries.es.po
DAMELIBRARIES_POT = ${srcdir}/damelibraries.pot

pdf: 
	texi2pdf $(DAMELIBRARIES)

pdf-es: 
	texi2pdf $(DAMELIBRARIES_ES)


html:
	texi2html $(DAMELIBRARIES)

info:
	makeinfo $(DAMELIBRARIES) 

clean:
	rm damelibraries.aux damelibraries.cp damelibraries.cps damelibraries.log damelibraries.toc *~

