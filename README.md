# Spring-school in Bioinformatics & Population Genomics

RNA-seq practicals created for the May/June 2016 [Spring School in Bioinformatics & Population Genomics ](https://www.isb-sib.ch/events/training/joint-spring-school-bioinformatics-and-population-genomics) organized by the [SIB PhD Training Network](https://www.isb-sib.ch/training/for-sib-phd-students) and the [Staromics](http://biologie.cuso.ch/staromics/welcome/) and [Ecology-Evolution](http://biologie.cuso.ch/ecologie-evolution/welcome/) doctoral programs.

## Prerequisites

We suppose that you are at ease:

 * with the command line. For a refresher, try the SIB's [UNIX fundamentals online course](http://edu.isb-sib.ch/course/view.php?id=82).
 * with R. The [swirl() library/course](http://swirlstats.com) can help. Follow the *R programming* self-led course (skip the sections *Simulation* and *Dates and Times*).

## Virtual Machine image

Our colleagues at [Vital-IT](http://vital-it.ch/) prepared a [Virtual Machine Image](ftp://ftp.vital-it.ch/edu/VM/ubuntuBPG.ova) that contains software and data. Use it by loading it into [Virtual Box](http://virtualbox.org). For detailed explanations and troubleshooting, check [the main course info page](http://edu.isb-sib.ch/course/view.php?id=252).

It may be feasible to do some of this stuff on a your favorite cluster or your local machine. However, it will be complicated. Among other things you'll need to install a bunch of [software](./software) and [data](https://github.com/wurmlab/GenomicsCourse/tree/219100ee0b1a42241010ddfc08836fb459560894/2016-SIB/data). Better to just use the Virtual Machine.


## Practicals
Available on this GitHub page:

* Gene expression:
     * [From raw sequencing data to transcript expression levels.](./practicals/rnaseq/TP1.md)
     * [Gene-level clustering and differential expression analysis.](./practicals/rnaseq/TP2.md)

Avialable on the [Wurm lab GitHub page](https://github.com/wurmlab/genomicscourse/blob/master/2016-SIB/practicals/index.md):

* Reads to genome to gene predictions:  Short read cleaning, genome assembly, quality control, gene prediction, quality control (Monday).
* Population sequencing to genotypes to population genetics statistics:
     * Mapping reads, calling variants, visualizing variant calls.
     * Analysing variants: PCA, measuring Differentiation & Diversity.
* Inferring population sizes and gene flow.


## Authors/Credits

These practicals were put together, revised and proofread by:
 * Rodrigo Pracana
 * Julien Roux [www](http://www.unil.ch/dee/home/menuinst/people/post-docs--associates/dr-julien-roux.html) [@_julien_roux](http://twitter.com/_julien_roux)

 * Robert Waterhouse [www](http://www.rmwaterhouse.org/) [@rmwaterhouse](http://twitter.com/rmwaterhouse)
 * Stefan Schiffels [@stschiff
](http://twitter.com/stschiff)
 * Yannick Wurm - [www](http://wurmlab.github.io) [@yannick__](http://twitter.com/yannick__)
 * with content derived from:
     * [Oksana Riba-Grognuz](https://www.linkedin.com/in/oksana80)' contributions for the 2012 edition of this course,
     * [Bruno Vieira](http://wurmlab.github.io/team/bmpvieira)'s contributions to [QMUL's Bioinformatics MSc](http://www.sbcs.qmul.ac.uk/postgraduate/masters/index.html) version of this course.

Thanks to Robin Engler, Ivan Topolsky and Vassilios Ioannidis & [Vital-IT](http://www.vital-it.ch) for putting together the Virtual Machine image for this course. And big credit to Gregoire Rossier for handling all the logistics of everything.
