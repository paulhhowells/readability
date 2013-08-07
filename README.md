readability
===========

How long should a line of text be?

I find very short and very long lines of text unpleasant, difficult, and possibly slow to read.  My experience tallies with typographic theory which states that this should be expected, and that there is an optimum range of widths for text.

Unfortunately there are multiple theories, research experiments and articles (to be found on the web) which disagree with each other over what the ranges of lengths are.  Some even come to the almost nihilistic conclusion of 'nobody agrees, so nobody knows, so don’t bother’.

As I care about the reading experience of folk who visit the websites we design and build I decided to do some informal research myself, thus this project.

goals
-----
* discover the ratio of (web browser) font-size to CPL (Characters Per Line)
* thus discover the column widths for a set of CPLs at common font sizes (12, 13, 14, 16, and 18px)
* gauge for myself the range of CPLs that are comfortable to read
* ask other people which range of CPLs they find comfortable to read


notes
-----
* CPLs include punctuation and spaces
* This github project is designed for testing digital. (But it would be fascinating to compare with print media).
* I’m not planning on running indepth, timed reading speed and comprehension tests with a diverse control and (large) test base (although this may well be valuable)
  * Such indepth research should also be careful to factor in screen size, physical type size (inches / mm) on the screen, and distance from reader.
  * Physical text width, angle (degrees) from the readers eye, should not be tested distinctly from CPLs.
* Initially I am not planning on testing the effect of leading on the results.  Without a doubt leading affects readability, so looking for an interaction with CPL would make sense
* I suspect there could also be a relation between preferred CPLs and the size of the article being read.


miscellaneous & related material
--------------------------------
(this is just a collection, not an endorsement of usefulness or validity)

* http://books.google.co.uk/books?id=7cLVq1UopTcC&pg=PA67&lpg=PA67#v=onepage
* http://stackoverflow.com/questions/7460041/whats-a-good-maximum-width-of-text-on-a-webpage
* http://www.usability.gov/get-involved/blog/2006/08/line-length-and-onscreen-reading.html
* http://www.pearsonified.com/2012/01/characters-per-line.php
* http://usabilitynews.org/the-effects-of-line-length-on-reading-online-news/