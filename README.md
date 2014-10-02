### Updates
This template was last updated in Fall 2014 for the 8th cycle of the NPRP.

### Introduction
This is a basic template to try and mimic the Qatar National Research Fund's
NPRP proposal template using Latex.  QNRF supplies an MS-Word template, but
I prefer to do my writing in Latex for a variety of reasons.

This template originally came to me from other sources, credits can be 
found inside.  I've simply packaged it up, updated it for recent cycles,
and distributed it.

### Disclaimer
This template is *not* official nor sanctioned by QNRF.  I make no guarantee
that they will accept a proposal that uses it.  However, it has been used
in previous cycles by a number of proposals without issue.

### Instructions
* Use this as the base for your proposal.

* When you compile it, make SURE you are using the letter paper size.  I do
the following:
  1. Run latex nprp.tex
  2. Run dvips -t letter -Ppdf nprp.dvi
  3. Run ps2pdf nprp.ps
* The paper size might still be wrong, so you'll need to verify it in a PDF viewer.  The truth is, getting paper size correct in Latex is sometimes painful.  Pray that it works for you.

### Known Bugs
* The title page in the QNRF template uses Cambria.  This is not easy to
use in Latex without horribly painful tricks.
* The Table of Content page doesn't look perfect, but I think its close enough.
