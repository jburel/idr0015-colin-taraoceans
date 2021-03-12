idr0015-colin-taraoceans
========================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IDR/idr0015-colin-taraoceans/master?urlpath=notebooks%2Fnotebooks%2FTara_Oceans_Geospatial.ipynb) 


Bulk-annotations CSV file
-------------------------

    virtualenv venv --system-site-packages
    venv/bin/pip install -r requirements
    venv/bin/python create_bulkanns.py

This should create a file `taraoceans.BULK_ANNOTATION.csv`.

Plate MapAnnotations
--------------------

    source venv/bin/activate
    ~/OMERO.server/bin/omero shell --login
    
    execfile('annotation_plates.py')

