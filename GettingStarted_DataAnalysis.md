Dworkin lab Guide to keeping yourself organized, efficient and sane before, during and after data analysis
===========================================================

## -This is a draft outline, not to be used yet.-

## Why be so precise about how we organize our data and analysis scripts?
- Make it easy and efficient for current use.
- Make it easy and efficient for future use.
- 
## Make your research reproducible from day one

## Data back up
[what you do not want](http://www.phdcomics.com/comics/archive.php?comicid=382)

##File formats
- Why we use flat text files
- Excel is ok for data entry, but not for long term storage
- Why we use .csv for "spreadhseets
- When to use relational databases
- Why you should do data transformations in your scripts and [not in the datafile](http://www.phdcomics.com/comics/archive.php?comicid=1323)

## Folder structures
- Why we have a recommended folder structure
- The recommended folder structure

```
    /projectName
           /data
           /scripts
           /outputs
           /figures
           /misc
           /manuscript
```           
- Example
- See blog postings that suggest why to use this.
 See [here](http://nicercode.github.io/blog/2013-04-05-projects/) for some ideas of how to organize your folders.
 [here as well](http://www.carlboettiger.info/2012/05/06/research-workflow.html)
[another one](http://www.sciencesurvivalblog.com/research-and-education/organizing-your-results_2920)
While [this](http://dx.plos.org/10.1371/journal.pcbi.1000424) article is written for computational biology projects, it holds in general.

## Scripting
- Philosophy for organizing scripts.
- Avoid doing [this](http://www.phdcomics.com/comics/archive.php?comicid=1323). 
- Source scripts (for functions) and analysis scripts.
- Syntax style guide for [R](https://www.msu.edu/~idworkin/ZOL851_style_guide.html)
- Syntax style guide for python

## Some brief notes on *Sanity Checks* during analysis
- Philosophy: Assume there are mistakes in the data and analysis until you convince yourself otherwise.
- Sanity checks on the computational process (Unit testing)
- Sanity checks on data (labeling, units, extra zeroes...)
- Sanity checks on the analysis
- Some important readings.
- 

## Resources for programming and analysis in R
 There are many many resoucres out there that you can find all over the web. In addition on the lab folders (the shared dropbox folder) there are PDFs of several useful books. Here are just a few additional links
[Nice R Code](http://nicercode.github.io/)

## Getting started using git and guthub
- What you [don't want](http://www.phdcomics.com/comics/archive.php?comicid=382)
- version control for scripts (and small data)
- 

## Reproducible research
- markdown vs. LaTeX
-- [mardown tutorial](http://daringfireball.net/projects/markdown/)
-- [github flavoured markdown](https://help.github.com/articles/github-flavored-markdown)
-- [github flavoured markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- knitR & sweave


