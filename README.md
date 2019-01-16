# How to submit your astronomy software and data reduction scripts

When you write an astronomy paper, you use software to carry out your data analysis. To generate the plots and figures you use a series of computer scripts that use this software and produce the graphical output as plots and figures.

If you haven't done so already, register for an [ORCID](https://orcid.org/) Identifier. The sites mentioned below have tight integration with ORCID, so it simplifies matters. Here is [my ORCID ID and page](http://orcid.org/0000-0002-7064-8270).

Procedure for software packages:

  * Learn [version control using GIT](http://nyuccl.org/pages/GitTutorial/) and how to upload your software to [github](https://github.com/). Make sure you choose a permissive license for your software - I have used the [BSD 3-clause license](https://github.com/mkenworthy/pds_110_exorings/blob/master/LICENSE).
  * Register the software at [Astrophysics Source Code Library](http://ascl.net/).  Currently, the ASCL accepts astronomy code that has appeared in a peer review research, submitted for peer review, or is an accepted astronomy thesis.  (Q: does this happen automatically or should you be active in it?)
  * Optionally upload it to [Zenodo](https://zenodo.org/) (Q: why Zenodo over any other storage place?)
  * If the package is not described in its own paper, consider submitted it to [Journal of Open Source Software](http://joss.theoj.org/)


Procedure for plots and figure scripts:

  * Code it in a Jupyter notebook and upload to github:
 example: [Analysis of PDS 110 photometry and making Figure 5](https://github.com/mkenworthy/pds_110_exorings) and it also automatically [displays your Jupyter Notebook](https://github.com/mkenworthy/pds_110_exorings/blob/master/plot_PDS_110_exoring_fig_5.ipynb)
  * Submit figures with accompanying explanation to [Figshare](https://figshare.com/).


## Citing astronomy software


  * Astropy from [Acknowledging Astropy](https://www.astropy.org/acknowledging.html) - We provide the following LaTeX/BibTeX acknowledgment if there is no specific place to cite the papers:

This research made use of Astropy,\footnote{http://www.astropy.org} a community-developed core Python package for Astronomy \citep{astropy:2013, astropy:2018}.
 
  * Scipy [Citing Scipy](https://www.scipy.org/citing.html)
 
  * Numpy [Citing Numpy](https://academia.stackexchange.com/questions/120718/cite-numpy-in-bibtex)
 
  * Matplotlib [Citing matplotlib](https://matplotlib.org/citing.html)
 
  * Pandas - cite McKinney 2010
  
  You can use the SciPy 2010 proceedings citation: 

    @InProceedings{ mckinney-proc-scipy-2010, 
      author    = { Wes McKinney }, 
      title     = { Data Structures for Statistical Computing in Python }, 
      booktitle = { Proceedings of the 9th Python in Science Conference }, 
      pages     = { 51 - 56 }, 
      year      = { 2010 }, 
      editor    = { St\'efan van der Walt and Jarrod Millman } 
    } 


## History of this document

v01 written by M Kenworthy based on Twitter conversations with Steve Crawford and Abigail Stevens on 2017 June 28
Putting it on github suggested by Thomas Robitaille
