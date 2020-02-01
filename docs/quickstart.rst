
.. |proj|  replace:: HaploTool
.. _proj: http://gobii-marker-tools-portal


Quick start
===========

You need a genomic variant dataset in either HapMap ( GOBii HapMap supported) or binary PLINK format.

The |proj| R package distribution comes with a few example rice datasets stored in the folder "extdata" 

A typical workflow could start like this:

Importing  data
-----------

  - In the **Import** tab,  browse to a genotype input file and select it. 
  In case of multiple files (e.g. a PLINK binary dataset -  *.bed*, *.bim*, and  *.fam* files), 
  select all files that constitute one dataset.

  - Select the file type in the dropdown and click *Import* button

If the file has been imported, you will see a new dataset name appear 
in the "Datasets" dropdown list in the navigation bar (navbar) on the left.

Similarly, you can input a phenotype file. Having a phenotype is not required, except for the last step - marker validation.



**Note.**  Haplotool is intended to be used with genotype data from a relatively short genomic region (so that number of distinct haplotypes is small). If you upload a genome-wide or chromosome-wide data, you will need to select a region in the *Filtering* tab, to have meaningful results.


Filtering and quality control
---------

This step is optional, althogh useful to perform on new datasets.

Clicking on the **Filter** menu in the navbar, one can perform various forms  of filtering and quality control.
( for details please go to  :doc:`/filtering`).

You can skip this step on your first run of |proj|.


Visualizing haplotype groups
----------------------------

Select the **Analysis** menu item in the navigation bar on the left.

Select any estimate of the number of haplotypes you expect to see in the genomic 


Marker validation
-----------------





