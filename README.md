Ada-VNP
=======
This repository includes the code for Virtual Network Protocol (VNP) middleware
written in Ada. Related project exists at [Github vn-sdm
project](https://github.com/virtual-network/vn-sdm), written in C and C++. The
work done in this repository is related to the master thesis report found at
[Github
project](http://github.com/christofferholmstedt/dva501-master-thesis-report).

### Status
As of January 2014 this work is about to start.

### Workflow
"Git-flow" workflow should be used for structuring the code instructions on
git-flow is found
[here](http://nvie.com/posts/a-successful-git-branching-model/). There is also
a collection of git extensions available at [Github project
nvie/gitflow](http://github.com/nvie/gitflow), though there is no need to use
that if you don't want to.

### Coding guidelines
[Ada Quality and Style Guide](https://en.wikibooks.org/wiki/Ada_Style_Guide).
Focus must be put on readability and maintainability.

##### Exceptions
1. Do not put with-clauses and use-clauses on the same line. Rationale: If a
   use clause is removed it's easier to spot the removal in "diffs".

### Version numbering
This project will use [Semantic Versioning 2.0.0](http://semver.org/) for
version numbers on releases.

### License
Not decided yet (January 2014).

### Issue tracker
The issue tracker on Github in this project will be used for all master thesis
related work, including questions about research methods and report details and
will be tagged appropriately.
