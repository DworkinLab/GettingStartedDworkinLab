Getting started with geometric morphometrics analysis in the Dworkin lab
========================================================================

## While this is a bit more than just a stub, much needs to be added.


## Introductory readings
Geometric Morphometrics for Biologists - We have a PDF of it in the lab dropbox space (so contact me for access to that space). We also have a physical copy that floats around the lab. This is a great introduction to the field, and has considerably depth to it.

[Morphometrics with R](http://ezproxy.msu.edu:2047/login?url=http://link.springer.com/openurl?genre=book&isbn=978-0-387-77789-4) - this is mostly useful once you are comfortable with the basics. When this was initially written, there was no single  `R` library but a collection of functions. Much of which is also available in `geomorph` or `shapes` in `R` (see below). However, this book goes through a lot of the algorithms and basic functions and thus remains quite useful.

## How to use wing machine (tutorials)
[From Will Pitchers](https://github.com/DworkinLab/WingMachine_manual)

## Software
[geomorph/R](http://www.geomorph.net/). Geomorph has really really gone a great way to develop a very general purpose set of analysis tools for morphometrics. Their blog has lots of useful tutorials and tips and tricks. Indeed, much of what we had originally written in `R` is now somewhat redundant. Since `geomorph` has a larger user base than our lab scripts, it is more likely that bugs in the code are to be found. Thus I recommend getting used to it. 

[Morpho/R](https://cran.r-project.org/web/packages/Morpho/index.html). Another `R` library for morphometrics. Some of the basiic tools overlap with `geomorph`, but there are many advanced plotting tools that differ. Also check out [the blog](http://zarquon42b.github.io/) associated with both `Morpho` and the authors other packages (i.e. `Rvcg`). The authors [github page also may be useful](https://github.com/zarquon42b).

[mvMORPH/R](https://cran.r-project.org/web/packages/mvMORPH/index.html). This is a relatively new R library for phylogenetic analysis using morphometrics data. I have not given it a whirl, but I am excited to try it out! The paper describing it is [here](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12420/full). It is probably very useful to also get familiar with both [`ape`/`R`](https://cran.r-project.org/web/packages/ape/index.html) and ['phytools'/'R'](https://cran.r-project.org/web/packages/phytools/index.html) which are some of the standard toolbox for such analyses.

[shapes/R](http://cran.r-project.org/web/packages/shapes/index.html). One of the older Geometric morphometrics libraries in `R`. 

[`StereoMorph`/`R`](https://cran.r-project.org/web/packages/StereoMorph/index.html). This `R` library is for acquisition of 3D data from relatively inexpsensive set ups (i.e. not requiring a micro-CT scanner). The library was also co-written by Annat Haber (a BEACON post-doc who collaborated with me on a couple of projects). Check out the [authors website](http://home.uchicago.edu/~aolsen/software/stereomorph.shtml) for more details. Also here is the [paper](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12420/full)

[MorphoJ](http://www.flywings.org.uk/MorphoJ_page.htm). This is a GUI based set of tools written in `Java`. It is very easy to use and get started with. While it is currently not set up for high throughput analyses (like GWAS), or for complicated mixed models, it can do a suprising number of analyses. I also use this to teach geometric morphometrics to my Evolutionary Developmental Biology Undergraduate class.

[StonyBrook morphometrics](http://life.bio.sunysb.edu/morph/) -  This includes access to [TPS software](http://life.bio.sunysb.edu/morph/) for morphometrics analysis, and links to many other useful resources.

## Links to Dworkin lab `.R` scripts and functions for morphometrics
Ok, so I need to really update this (currently most of the development scripts are in the shared dropbox space). However, some of the older (and archived versions of our analysis pipelines can be found in the github repositories associated with our papers.

[Pitchers et al. 2014](https://github.com/DworkinLab/PitchersJEB2014_cricket_wings)
[Sonnenschein et al 2015](https://github.com/DworkinLab/Wing_Biometrics_2015)


## Other useful resources
[Morphometrics Library](http://morpholib.eu.pn/cms/)

[morpho-tools](http://morpho-tools.net/)

[Evolutionary Morphing](http://www.idav.ucdavis.edu/research/EvoMorph). Awesome visualizations!

## Various databases
[phenome 10k](http://phenome10k.org/)

[facebase](https://www.facebase.org/)

[Morphbank](http://www.morphbank.net/). I think this is the database that David Houle has put all of his Drosophila wings on.

[GigaDB](http://gigadb.org/dataset/100141). This is where we hosted all of the images (I think ~6000) for a Drosophila wing dataset. All images, flat files with landmarks and scripts are available here. The scripts and landmarks are also on the DworkinLab github.
