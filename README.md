VaR-Rule for FX Interventions
================================

This Python notebook replicates the tables and the charts of the IMF WP on Foreign Exchange Intervention Rules for Central Banks.
It uses a Python package that I have written, DistGARCH, also available in this Github folder, with the public FX intervention data from the Banco Mexico. DistGARCH is based on the ARCH package of Kevin Sheppard.

You can use the code for non-commercial applications, providing that you cite the IMF Working Paper
Lafarguette, R. and Veyrune, R. (2020) VaR-Rule for FX Interventions, IMF Working Paper no 20XX

The folder is organized as follows:
- VaR-FX Interventions.ipynb replicates the results of the paper
- modules/ contains the modules for this project, in particular distGARCH which infers a conditional distribution from a GARCH model
- data/ contains public data files, with FX rate and FX interventions from Banco Mexico website
- img/ contains some images to illustrate the Jupyter Notebook

**Reuse of this  tool and  IMF data  does not  imply any  endorsement of  the
research  and/or product.  Any research  presented should  not be  reported as
representing  the   views  of  the   IMF,  its  Executive  Board,   or  member
governments.**

Note that the Github repo contains only publicly available data. 

Author: Romain Lafarguette, August 2020
If you have any question, please contact me via Github or rlafarguette "at" imf "dot" org
