Princeton University Student Origins

Interactive map of the origins of students between 1784 and 1865.

Extra tools required:
rake
ogr2ogr
unzip
nodejs
topojson (v1)
xlsx

rake, ogr2ogr, unzip, and nodejs can be installed via the package manager.

topojson must be installed via nodejs (npm -g topojson@1); xlsx is also installed via nodejs.

The name of the student data spreadsheet must be correctly specified in the Rakefile.

To generate the .json files, do "rake clean" then "rake"; any missing geometry files will be automatically downloaded.

Styling is done via the index.html file (could be moved to a dedicated .css file if desired).

Modifications to the size of the map, positioning of elements, etc is done via the variables at the top of the visualization.js file.

Based on the "Historical Boundaries of the United States" project by Lincoln A. Mullen (http://lincolnmullen.com/projects/us-boundaries/)
