# command-line-tools
A disparate set of command line tools that have found some purpose over the span of this project.

Many of these are more fragmented, very specific-purpose, e.g. debug tools, so not so generally interesting.

Some are specific projects and worth some readingif they sound like something you need.


## XML helpers 

Separate helpers scripts that were used mainly to figure out the BWB XMLs's relatively free-form document structure,
and some other explanatory and exploratory uses.  

`xml-color` will pretty-print XML files to the console with colors and options to e.g. remove namespaces

`xml-path-statistics` counts how often each path occurs in an XML file, potentially useful to estimate structure when writing code to extract specific things

`xml-text` will print only the text content, as a quick but dirty 'give me some text to play with'

They rely on the wetsuite.helpers.etree module, which makes them slightly specialized,
also in that we have a bunch of namespaces that xml-color prints with our own preferred abbreviation.
