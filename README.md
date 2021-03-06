[![Build Status](https://travis-ci.org/stephlocke/chartgallery.svg?branch=master)](https://travis-ci.org/stephlocke/chartgallery)

There's so many R graphics packages these days and I wanted to be able to see how they all perform different charting tasks.

## Covered packages
- ggplot2
- vegalite
- ggvis

## Thanks
Very much inspired by [\@hrbrmstr](https://github.com/hrbrmstr) and my thanks to everyone who has invested the time into making one of the packages used here.

## Contribute
If you'd like to contribute some charts for a package:

1. Clone the repo
2. Make sure you can run charting.Rmd locally
3. Copy the skeleton files and name with the package you want to use
4. Within the Rmd template, amend the R file name to be sourced
5. Add some useful info about the package to the Rmd
6. Use the setup chunk in the R file to install any necessary packages
7. Complete any of the subsequent sections and add additional chart types if desired. Match the contents of the same section for other libraries. Make each section standalone - so do repeat any aggregations etc required.
8. Once the charts all work, add the Rmd as a child item to charting.Rmd and verify charting.Rmd works
