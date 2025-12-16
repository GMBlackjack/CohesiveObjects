This GitHub repository contains supplementary files for the paper "The Cohesive Object Sequence: Continuity in the Mass-Density Distribution From Asteroids to Stars" by Gabriel M Steward (me, the one writing this README) and Matthew Hedman. 

[Insert link to paper and doi and other things]

This repository only contains a few files, including this README (Hello!) and a LICENSE that is the basic Creative Commons BY 4 license.

The primary file of interest is ObjectsInfoMRT.csv, a comma separated value spreadsheet with all the data used to create the plots in the paper. Each "cohesive object" is on a single line of the csv. Every line follows this pattern:

Name,
Mass (earth masses),
Upper Mass Error (earth masses),
Lower Mass Error (earth masses),
Radius (earth radii),
Upper Radius Error (earth radii),
Lower Radius Error (earth radii),
Object Classification,
Source,
Another Source,
More Sources if Needed, 
etc.

This repository also comes with a jupyter notebook (objectReaderPrinter.ipynb) that interprets the data using python code, producing plots. All the plots used in the paper and several others are produced in it. It'd designed to work no matter what is in ObjectsInfoMRT.csv, so it could easily produce plots for an expanded or restricted list of cohesive objects. (Though adding an entirely new Object Classification would involve manually tinkering with the code.) 

Lastly, the file ObjectsPosterLargeText.pdf is a poster presented on this research prior to the paper's publication. Do note that it was presented prior to the paper's finalization, so the paper is the final word on everything. (I do believe some objects were removed from the data set after the poster was presented, for instance). 

Feel free to use anything in this repository however you want, just make sure to give credit when doing so.

-GM


