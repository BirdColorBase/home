# BirdColorBase
A database of bird color data from spectrophotometry

![example of spectrum](/birdcolorbase_logo.jpg)

BirdColorBase is a database of "color" data from over 2500 species of birds from around the world.  

The data (specta) were collected with spectrophotometers from specimens at numerous museums as well as from live birds. 
Birds can see in the ultraviolet portion of the spectrum so spectrophotometers are needed to describe the full range of color that birds possess and can see when communicating.  These data also provide a standardized light environment for measurement of "color" which can vary depending on ambient light and the angle of the bird to the observer.

The database contains files with readings of percent reflectance across the bird-visible spectrum (300 to 700 nm).  These spectra were averaged into 2 nm bins (eg, 300-302, 302-304 etc). Most of the data were collected using an Ocean Optics (Dunedin, Florida) USB2000 spectrophotometer and a PX-2 pulsed Xenon light source with the spectrophotometer probe illuminating and measuring at 90° to the plumage. Measurements were standardized to a white standard (WS-1, Ocean Optics), considered >98% reflective from 250 to 1500 nm wavelengths. Spectra are arranged in rows, one line for each species and "patch" on the bird.  Some patches were repeatedly measured which can be inferred from multiple measurements of the same "individual".

## File info
There are separate files from different research groups to keep the file sizes relatively small for uploading. Each file contains metadata with information on species names and taxonomy, catalog informatiion where available and raw spectra (percent reflectance from 300 to 700 nm in 2 nm bins).  Studies using these files are listed below under references. Please consult them for additional information. 

## License
These data are licensed under the MIT license and are free to use with appropriate acknowledgment of this database (add ref).

## Acknowledgements
BirdColorBase was originally started in 2017 by Thahn-Lan Gluckman and John Endler, who cleaned the original spectra and produced the binned files in this database. We thank the curators and collection managers of the following museums for access to specimens: Academy of Natural Sciences (Philadelphia), American Museum of Natural History (New York), Auckland Museum, Australian National Wildlife Collection (Canberra), California Academy of Sciences (San Francisco), Field Museum of Natural History (Chicago), Louisiana State University Museum of Natural Science (Baton Rouge), Moore Lab of Zoology at Occidental College (Los Angeles), Museum National d'Historie Naturelle (Paris), Museum Victoria (Melbourne), Natural History Museum (Tring), and National Museum of Natural History (Washington, D.C.). 

## Contributors
The source column in the data files refer to these contributors:

Jessica K. Armenta,
Kevin Burns,
Gonçalo Cardoso,
James Dale,
Claire Doutrelant,
Peter O. Dunn,
Jamie Dunning,
Muir Eaton,
John Endler,
Amélie Fargevieille, 
Ana Cristina Gomes, 
Doris Gomez,
Rafael Maia,
Paulo Mota,
Richard Prum,
Allison Shultz,
Mary C. Stoddard,
Linda A. Whittingham


## References

Armenta, J. K., P. O. Dunn, and L. A. Whittingham. 2008. Quantifying avian sexual dichromatism: a comparison of methods. J Experimental Biology 211:2423-2430.

Cardoso, G. C., and P. G. Mota. 2008. Speciational evolution of coloration in the genus Carduelis. Evolution 62:753-762.

Doutrelant, C., M. Paquet, J. P. Renoult, A. Gregoire, P. A. Crochet, and R. Covas. 2016. Worldwide patterns of bird colouration on islands. Ecology Letters 19:537-545.

Dunn, P. O., J. K. Armenta, and L. A. Whittingham. 2015. Natural and sexual selection act on different axes of variation in avian plumage color. Science Advances 1:10.1126/sciadv.1400155.

Dunning, J., C. Sheard, and J. A. Endler. 2025. Viewing conditions predict evolutionary diversity in avian plumage colour. Proceedings of the Royal Society B: Biological Sciences 292:20241728.

Eaton, M. D. 2005. Human vision fails to distinguish widespread sexual dichromatism among sexually "monochromatic" birds. Proceedings of the National Academy of Sciences, USA 102:10942-10946.

Fargevieille, A., A. Grégoire, D. Gomez, and C. Doutrelant. 2023. Evolution of female colours in birds: The role of female cost of reproduction and paternal care. Journal of Evolutionary Biology 36:579-588.

Gomez, D., and M. Théry. 2007. Simultaneous crypsis and conspicuousness in color patterns: comparative analysis of a neotropical rainforest bird community. American Naturalist 169:S42-S61.

Maia, R., D. R. Rubenstein, and M. D. Shawkey. 2016. Selection, constraint, and the evolution of coloration in African starlings. Evolution 70:1064–1079.

Shultz, A. J., and K. J. Burns. 2017. The role of sexual and natural selection in shaping patterns of sexual dichromatism in the largest family of songbirds (Aves: Thraupidae). Evolution 71:1061–1074. 

Stoddard, M. C., and R. O. Prum. 2011. How colorful are birds? Evolution of the avian plumage color gamut. Behavioral Ecology 22:1042-1052.

## Funding

Please see the references above for funding sources for the original spectrophotometry data.



