.. HaploTool documentation master file, created by
   sphinx-quickstart on Thu Mar  7 10:24:53 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. |proj|  replace:: HaploTool
.. _proj: http://gobii-marker-tools-portal

|proj|'s documentation!
===================================

Contents:

.. toctree::
   :maxdepth: 1

   ../quickstart
   ../filtering.rst
   ../analysis.rst

|proj|
=======

|proj|_ helps to visualize genomic region of interest (e.g. candidate gene region) and associate haplotype goups to phenotype.
It can be used to validate markers by visually and analytically confirming association of a marker with a haplotype that is associated to desirable trait.

See :doc:`/quickstart` page for an example of basic usage.


Features
--------

- Import data in various formats (HapMap, PLINK)
- Marker and sample QC and filtering  ( see :doc:`/filtering` )
- Haplotype clustering into groups and visualization
- Visualization of phenotype along with genotype ordered according to haplotype groups
- Testing association between markers and haplotypes



Install
-------
You can use |proj| running as an online service on GOBii Marker Portal (link), or you can install it on your local machine as follows:

 1. Download R package archive (link)  
 2. If you have RStudio:

  - Go to menu Tools -> Install Packages
  - In the "Install from.." dropdown, select "Package Archive File" and click "Install"


Contribute
----------

- Issue Tracker: github.com/$project/$project/issues
- Source Code: bitbucket.com/gobii/$project/|project|


Support
-------

If you are having issues, please let us know at
|proj| @google-groups.com

Bug reports are welcome.


License
-------
|proj| is licensed under [ Apache 2.0 license. ]










