Getting started with geometric morphometrics analysis in the Dworkin lab
========================================================================

## While this is a bit more than just a stub, much needs to be added.


## Introductory readings
Geometric Morphometrics for Biologists - We have a PDF of it in the lab dropbox space (so contact me for access to that space). We also have a physical copy that floats around the lab. This is a great introduction to the field, and has considerably depth to it.

[Morphometrics with R](http://ezproxy.msu.edu:2047/login?url=http://link.springer.com/openurl?genre=book&isbn=978-0-387-77789-4) - this is mostly useful once you are comfortable with the basics. When this was initially written, there was no single  `R` library but a collection of functions. Much of which is also available in `geomorph` or `shapes` in `R` (see below). However, this book goes through a lot of the algorithms and basic functions and thus remains quite useful.

## Software
[geomorph/R](http://www.geomorph.net/). Geomorph has really really gone a great way to develop a very general purpose set of analysis tools for morphometrics. Their blog has lots of useful tutorials and tips and tricks. Indeed, much of what we had originally written in `R` is now somewhat redundant. Since `geomorph` has a larger user base than our lab scripts, it is more likely that bugs in the code are to be found. Thus I recommend getting used to it. 

[Morpho/R](https://cran.r-project.org/web/packages/Morpho/index.html). Another `R` library for morphometrics. Some of the basiic tools overlap with `geomorph`, but there are many advanced plotting tools that differ. Also check out [the blog](http://zarquon42b.github.io/) associated with both `Morpho` and the authors other packages (i.e. `Rvcg`). The authors [github page also may be useful](https://github.com/zarquon42b).

[mvMORPH/R](https://cran.r-project.org/web/packages/mvMORPH/index.html). This is a relatively new R library for phylogenetic analysis using morphometrics data. I have not given it a whirl, but I am excited to try it out! The paper describing it is [here](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12420/full). It is probably very useful to also get familiar with both [`ape`/`R`](https://cran.r-project.org/web/packages/ape/index.html) and ['phytools'/'R'](https://cran.r-project.org/web/packages/phytools/index.html) which are some of the standard toolbox for such analyses.

[shapes/R](http://cran.r-project.org/web/packages/shapes/index.html). One of the older Geometric morphometrics libraries in `R`. 

[MorphoJ](http://www.flywings.org.uk/MorphoJ_page.htm). This is a GUI based set of tools written in `Java`. It is very easy to use and get started with. While it is currently not set up for high throughput analyses (like GWAS), or for complicated mixed models, it can do a suprising number of analyses. I also use this to teach geometric morphometrics to my Evolutionary Developmental Biology Undergraduate class.

[StonyBrook morphometrics](http://life.bio.sunysb.edu/morph/) -  This includes access to [TPS software](http://life.bio.sunysb.edu/morph/) for morphometrics analysis, and links to many other useful resources.

## Links to Dworkin lab `.R` scripts and functions for morphometrics
