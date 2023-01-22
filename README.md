# isiscalendar.github.io
Shows information about events held on the Isis (the stretch of Thames in central Oxford).

isis-calendar
A very simple Hugo-powered site that keeps all the info about what's happening on the Thames.

Originally managed via https://github.com/annarailton/isis-calendar but now managed https://github.com/isiscalendar/isiscalendar.github.io.

The website lives at https://isiscalendar.github.io/

To get something added or for corrections to the content please open a PR or email info@isiscalendar.org.uk

Location of data
Data is all under the content directory, in appropriately named .md files (link to markdown cheatsheet). Nothing else should need changing unless you want to play with how the site looks.

Running locally
You'll need both golang and Hugo installed:

Install go
Install Hugo
Check that it all works by doing

hugo version
Clone this repo, navigate to the top of the folder and do

hugo server -D
You can then see the site on localhost - the prompt will tell you which port.

Other
Hugo theme is https://github.com/panr/hugo-theme-terminal by panr
