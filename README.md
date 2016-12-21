# Dave Tang's curriculum vitae

My C.V. can be viewed and downloaded at <https://github.com/davetang/cv/blob/master/cv.pdf>. If viewing directly on GitHub, the hyperlinks will not work, although they will still appear blue. Links in my C.V. are included to provide elaboration and for convenience. I remember seeing a thread on Twitter discussing whether one should include URLs in their C.V. for their own publications and the consensus was that it should be avoided. I honestly think it's useful, so I have left them in.

## Creating the PDF

On Ubuntu install these packages:

~~~~{.bash}
sudo apt-get update
sudo apt-get install texlive texlive-latex-extra
~~~~

On OS X, install [MacTeX](http://www.tug.org/mactex/).

The `to_pdf.sh` script will create the final PDF.

~~~~{.bash}
to_pdf.sh cv.tex
~~~~

