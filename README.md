# Learning Bioinformatics At Home

Some resources gathered by the [Harvard Informatics group](https://informatics.fas.harvard.edu) and other contributors to help people learn bioinformatics tools (basic and specialized) at home.

## Table of content

- [Unix](#unix)
  - [Introduction](#introduction)
  - [Intermediate](#intermediate)
  - [Advanced](#advanced)
- [R](#r)
  - [Introduction](#introduction-1)
  - [Intermediate](#intermediate-1)
  - [Advanced](#advanced-1)
- [Python](#python)
  - [Introduction](#introduction-2)
  - [Intermediate](#intermediate-2)
  - [Advanced](#advanced-2)
- [Statistics](#statistics)
- [Git and version control](#git-and-version-control)
- [RNA-seq](#rna-seq)
- [Single-cell Analysis](#single-cell-analysis)
- [Read mapping](#read-mapping)
- [Variant calling](#variant-calling)
- [Miscellaneous](#miscellaneous)

### Unix

#### Introduction

* [Greg Wilson's YouTube videos on the Unix shell](https://www.youtube.com/watch?v=U3iNcBtycaQ)
* [Introduction to the Command Line for Genomics](https://datacarpentry.org/shell-genomics/)
* [A short introduction to grep](https://informatics.fas.harvard.edu/short-introduction-to-grep.html)
* [Lockdown Learning - Bioinformatics](https://www.youtube.com/playlist?list=PLzfP3sCXUnxEu5S9oXni1zmc1sjYmT1L9): Daily livestreamed bioinformatics lessons, assuming no prior experience. 

#### Intermediate
* [Advanced Beginner/Intermediate Shell](https://github.com/ngs-docs/2016-adv-begin-shell-genomics)

#### Advanced

* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [Better Bash Scripting in 15 Minutes](http://robertmuth.blogspot.com/2012/08/better-bash-scripting-in-15-minutes.html?m=1)
* [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls)
* Process Substitution
    - [Using Names Pipes and Process Substitution in Bioinformatics](http://vincebuffalo.org/blog/2013/08/08/using-names-pipes-and-process-substitution-in-bioinformatics.html)
    - [Handy Bash feature: Process Substitution](https://medium.com/@joewalnes/handy-bash-feature-process-substitution-8eb6dce68133#.uz5pj9yer)

* One-Liners for Bioinformatics
    - [From Steven Turner](https://github.com/stephenturner/oneliners)
    - [From Ming (Tommy) Tang](https://github.com/crazyhottommy/bioinformatics-one-liners)

### R

#### Introduction
* [Data Analysis for the Life Sciences Series](http://rafalab.github.io/pages/harvardx.html): A course by Rafael Irizarry at Dana Farber
* [Introduction to Computational Biology](https://biodatascience.github.io/compbio/): Tutorial by Mike Love, the author of DESeq2 and other R packages

#### Intermediate
* [Introduction to Bioconductor](https://www.edx.org/course/introduction-to-bioconductor-annotation-and-analys): The structure, annotation, normalization, and interpretation of genome scale assays (free edX course)
* [R for data science](https://r4ds.had.co.nz/): by Hadley Wickham, developer of Tidyverse and many other things


#### Advanced
* [Advanced Bioconductor](https://www.edx.org/course/advanced-bioconductor): Learn advanced approaches to genomic visualization, reproducible analysis, data architecture, and exploration of cloud-scale consortium-generated genomic data (free edX course)
* [Advanced R](https://adv-r.hadley.nz/): Advanced course by Hadley Wickham
* [Bioconductor courses and conferences](https://www.bioconductor.org/help/course-materials/): Overview of Bioconductor training resources

### Python

#### Introduction
* [Using Python for Research](http://rafalab.github.io/pages/harvardx.html) A collection of links to YouTube videos; scroll to the bottom.
* [Biology Meets Programming: Bioinformatics for Beginners](https://www.coursera.org/learn/bioinformatics)

#### Intermediate
* [Intermediate Python](https://github.com/yasoob/intermediatePython)
* [Checkio](https://py.checkio.org/): Python coding game, great for practice!

#### Advanced

### Statistics

* [Modern Statistics for Modern Biology](http://web.stanford.edu/class/bios221/book/index.html): Book by Susan Holmes and Wolfgang Huber

### Git and version control

* [github learning lab](https://lab.github.com/)
* [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
* [Happy Git and GitHub for the useR](http://happygitwithr.com/): A book by Jenny Bryan
* [learn git branching](http://learngitbranching.js.org/)
* [A Git Workflow Walkthrough Series](http://vallandingham.me/git-workflow.html)
* [paper:A Quick Introduction to Version Control with Git and GitHub](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668)
* [paper:Ten Simple Rules for Taking Advantage of Git and GitHub](http://journals.plos.org/ploscompbiol/article?id=10.1371%2Fjournal.pcbi.1004947)
* [software carpentry git novice lesson](http://swcarpentry.github.io/git-novice/)
* [git best practice](https://sethrobertson.github.io/GitBestPractices/)
* [git-hub cheatsheet](https://github.com/tiimgreen/github-cheat-sheet#readme)
* [git in practise](https://github.com/GitInPractice/GitInPractice#readme): An opinionated intermediate/advanced Git book

* Fixing Problems: Git is hard, and screwing up is easy, and figuring out how to fix your mistakes is impossible. Git documentation has this chicken and egg problem where you can't search for how to get yourself out of a mess, unless you already know the name of the thing you need to know about in order to fix your problem. Here are resources to help figure out what to do when things go wrong.

    - [oh shit git!](http://ohshitgit.com/)
    - [How to undo (almost) anything with Git](https://github.com/blog/2019-how-to-undo-almost-anything-with-git)
    - A guide for astronauts (now, programmers using Git) about what to do when things go wrong: git flight rules](https://github.com/k88hudson/git-flight-rules)

### RNA-seq

### Single-cell Analysis

* [Harvard Informatics One-Day Intro](https://crazyhottommy.github.io/scRNA-seq-workshop-Fall-2019/)
* [Guided Analyses with Seurat](https://satijalab.org/seurat/vignettes.html)

### Read mapping

### Variant calling

* [Harvard Informatics fastq to VCF](https://informatics.fas.harvard.edu/whole-genome-resquencing-for-population-genomics-fastq-to-vcf.html). Targeted for non-model organisms.
* RAD-seq tutorials from dDocent on [Reference Assembly](http://www.ddocent.com/assembly/) and [SNP filtering](http://www.ddocent.com/filtering/)

### Miscellaneous

* [Understanding snakemake](https://vincebuffalo.com/blog/2020/03/04/understanding-snakemake.html) An overview from Vince Buffalo, author of Bioinformatics Data Skills
* [A Primer for Computational Biology](https://open.oregonstate.education/computationalbiology/) A nice book.
* [Fundamentals of Data Visualization](https://serialmentor.com/dataviz/): Claus Wilke's book on data visualization, covers principles and figure design.
* [gcp-for-bioinformatics](https://github.com/lynnlangit/gcp-for-bioinformatics) a repo with patterns for using the public cloud for bioinformatics, uses GCP, but patterns can be applied to other public cloud vendors, i.e. AWS, Azure....
* [SLiM workshops](http://benhaller.com/workshops/workshops.html) Extensive tutorial for using SLiM, a population genetic simulation environment
