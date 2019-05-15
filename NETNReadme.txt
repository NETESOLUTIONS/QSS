%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
MIT Press 
>>Network Neuroscience<< Journal LaTeX Package

Written by Amy Hendrickson
amykaren@mit.edu
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

22 Files and what they are used for:

%%%%%%%%%%%%%%%%%%
Basic macro file:
%%%%%%%%%%%%%%%%%%

stjour.cls   
  Used: \documentclass[NETN]{stjour}
  Or, for double spaced manuscript form: 
        \documentclass[manuscript]{stjour}
        \journalname{Network Neuroscience} 
        (\journalname{} only needed when [manuscript] option is used.)

  Final Production only (authors not required to do this)
  Used: \documentclass[finalfonts,NETN]{stjour}

NETN-OTF-Fonts.zip OTF fonts for final production

%%%%%%%%%%%%%%%%%%
Graphics files:
%%%%%%%%%%%%%%%%%%

NETN_logo.eps/pdf Logo for opening page.

fig1.eps/.pdf For use in NETNSample. 
              Figure sample file in .eps form for dvips, and .pdf
	      form for pdflatex. 

colophon.pdf/.eps 
Cross-Mark.pdf/.eps 
openaccess3.pdf/.eps
             All files needed for formatting first page of article.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\subsection{Sample Files}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

NETNSample.tex/.pdf Sample file to see the LaTeX commands
in use, and to compare with the resulting typeset document

NETNSample.bbl    Sample bibliography file made with BibTeX

NETNbibsamp.bib   Sample bibliography database file for use with
                      BibTeX to use with NETNSample.

ManuscriptSample.tex/.pdf Sample files to show manuscript option in
                          use.
                     \documentclass[manuscript]{stjour}
ManuscriptSample.bbl       Sample .bbl file to build bibliography in ManuscriptSample


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Template File
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

NETNTemplate.tex  For authors to copy and rename  when making
                      their own article.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Documentation
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

NETNDocs.pdf

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

NETNReadme.txt   this file