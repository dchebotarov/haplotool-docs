.. HaploTool documentation master file, created by
   sphinx-quickstart on Thu Mar  7 10:24:53 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. |proj|  replace:: HaploTool
.. _proj: http://gobiin1.bti.cornell.edu:6083/projects/UT/repos/haplotool/browse/HaploTool

|proj|'s documentation
===================================

Contents:

.. toctree::
   :maxdepth: 1

   filtering.rst
   analysis.rst

Overview
========

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
You can use |proj| running as an online service on GOBii Marker Portal (link), or you can install it on your local machine either as R package or using Docker. 

The details are described on the Bitbucket page:

http://gobiin1.bti.cornell.edu:6083/projects/UT/repos/haplotool/browse/README.md

Briefly, there are two options, we recommend using Docker.

1) Installing using R Studio

  1. Download R package archive ( `link <http://gobiin1.bti.cornell.edu:6083/projects/UT/repos/haplotool/browse/HaploTool.tar.gz>`  )  

  2. In  RStudio:

    - Go to menu Tools -> Install Packages
    - In the "Install from.." dropdown, select "Package Archive File" and click "Install"

2) Instal and run using Docker:

.. code:: bash

  docker run -dti \
  --name=shiny_app \
  -h shiny-node \
  -v /home/gadm/workspace/haplotool:/home/shiny/haplotool \
  --user shiny \
  --rm \
  -p 80:3838 \
  gadm01/haplotool:v0.1


Contribute
----------

.. .. - Issue Tracker: github.com/$project/$project/issues
- Source Code: http://gobiin1.bti.cornell.edu:6083/projects/UT/repos/haplotool/browse 


Support
-------

If you are having issues, please let us know at d [dot] chebotarov [at] irri.org

Any feedback (bugs, feature requests)  is  welcome.


License
-------
.. .. |proj| is licensed under [ Apache 2.0 license. ]

|proj| will be licensed under an open source license suitable for GOBii project 
once it is published. 
Please check back for updates.


.. include:: authors.rst



