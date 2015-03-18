# Readme #

**Install**

`npm install search-and-replace --save`

**Usage**

This utility created in order to give a cli tool for replacing regex within a file without throwing an error if the file or part of the path not exists.  
This utility replace a regex with replacement within a found file in some path. If file not found nothing happens.  

`search-and-replace filename path regex replacement`

**Example**

`search-and-replace.js index.js ./node_modules/gaze \\.\\/lib\\/gaze\\.js ./lib/gaze04.js"`

