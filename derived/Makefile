#
# generate report in various formats
#
# required packages on Debian: pandoc, texlive-latex-base, texlive-fonts-recommended
#
SRCDOC=../Report_of_the_Code4Lib_Fiscal_Continuity_Interest_Group.md

all: fcig_report.pdf fcig_report.mediawiki.txt

fcig_report.pdf: $(SRCDOC)
	pandoc -t latex -o fcig_report.pdf $(SRCDOC)
fcig_report.mediawiki.txt: $(SRCDOC)
	pandoc -t mediawiki -o fcig_report.mediawiki.txt $(SRCDOC)
