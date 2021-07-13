# Jasmine targetlist

```
jasmine_target_getlist.ipynb
jasmine_target_xmatch_gaiadr2_2mass.ipynb
jasmine_target_xmatch_gaiaedr3_2mass.ipynb
jasmine_target_xmatch_or_gaiaedr3_2mass.ipynb
jasmine_target_xmatch_sirius_gaia3_prototype.ipynb
```

GAIA EDR3 and 2MASS xmatch catalog from GAIA archive : /home/omiya/jasmine_targetlist/xmatch_gaiaedr3_2MASS_3x3.csv  
GAIA DR2 and 2MASS xmatch catalog from GAIA archive : /home/omiya/jasmine_targetlist/xmatch_gaiedr2_2MASS_3x3.csv  
Sirius catalog : /home/omiya/jasmine-targetlist/SIRIUS/WGCCatAll.dat 

Star lists in a small region in a directory of /home/omiya/jasmine-targetlist/ on jasmine GPU server
- gaiaedr3_v1.csv  
- twomass_v1.csv
- gsc_v1.csv
- vvv_v1.csv  
- galacticnucleus_v1.csv  
- sirius_v1.csv  
  
  
- xmatch_gaiaedr3_2MASS_v1.csv  (by jasmine_target_getlist.ipynb)
- xmatch_gaiaedr3_2MASS_v2.csv  (by jasmine_target_xmatch_gaiaedr3_2mass.ipynb @jasmine regions)
- xmatch_gaiaedr3_2MASS_v3.csv  (by jasmine_target_xmatch_or_gaiaedr3_2mass.ipynb)
- xmatch_or_gaiaedr3_2MASS_v3.csv  (by jasmine_target_xmatch_or_gaiaedr3_2mass.ipynb)
- xmatch_sirius_gaiaedr3_v0.csv  (by jasmine_target_xmatch_sirius_gaia3_prototype.ipynb)
- xmatch_gaiadr2_2MASS_v2.csv  (by jasmine_target_xmatch_gaiaedr3_2mass.ipynb @jasmine regions)

Package requirements
```
numpy
pandas
astropy
astroquery
tqdm
multiprocessing
matplotlib
```

