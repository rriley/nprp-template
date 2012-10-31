### Introduction
This is a basic template to try and mimic the Qatar National Research Fund's
NPRP proposal template using Latex.  QNRF supplies an MS-Word template, but
I prefer to do my writing in Latex for a variety of reasons.

This template originally came to me from other sources, credits can be 
found inside.  I've simply packaged it up, updated it for the 6th cycle,
and distributed it.

### Instructions
* Use this as the base for your proposal.

* When you compile it, make SURE you are using the letter paper size.  I do
the following:
  1. Create .dvi file with latex
  2. Run dvips -t letter -Ppdf nprp.dvi
  3. Run ps2pdf nprp.ps

* This produces a document that has the research plan and the references in
the same file.  QNRF wants them separate.  You'll need to split the PDF
into two different documents.  I use Acrobat Pro, but there are numerous
free tools that can do it as well.  http://www.pdfsam.org/ looks reasonable.

### Known Bugs
* The title page in the QNRF template uses Cambria.  This is not easy to
use in Latex without horribly painful tricks.
* The Table of Content page doesn't look perfect, but I think its close enough.
