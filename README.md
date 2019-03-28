# gaiadr2-ruwe-tools
Python code for calculating the Renormalized Unit Weight Error from the Gaia DR2 table columns.

One of the [recommendations on the use of Gaia DR2 astrometry](https://www.cosmos.esa.int/web/gaia/dr2-known-issues#AstrometryConsiderations) 
is to use the so-called Renormalized Unit Weight Error (RUWE) to filter out sources with potentially bad astrometry, in particular
spurious parallaxes or proper motions. Details are in these [presentation slides](https://www.cosmos.esa.int/documents/29201/1770596/Lindegren_GaiaDR2_Astrometry_extended.pdf/1ebddb25-f010-6437-cb14-0e360e2d9f09) and
in [this technical note](http://www.rssd.esa.int/doc_fetch.php?id=3757412).

This repository provide Python code for calculating the value of the RUWE from the relevant table columns in the Gaia DR2 Archive.
An accompanying notebook shows how to use the code by reproducing one of the plots in the above mentioned presentation slides.
