# BirdColorBase
A database of bird color data from spectrophotometry

![example of spectrum](/birdcolorbase_logo.jpg)

BirdColorBase is a database of "color" data from over 2500 species of birds from around the world.  

The data (specta) were collected with spectrophotometers from specimens at numerous museums as well as from live birds. 
Birds can see in the ultraviolet portion of the spectrum so spectrophotometers are needed to describe the full range of color that birds possess and can see when communicating.  These data also provide a standardized light environment for measurement of "color" which can vary depending on ambient light and the angle of the bird to the observer.

The database contains files with readings of percent reflectance across the bird-visible spectrum (300 to 700 nm).  These spectra were averaged into 2 nm bins (eg, 300-302, 302-304 etc). Most of the data were collected using an Ocean Optics (Dunedin, Florida) USB2000 spectrophotometer and a PX-2 pulsed Xenon light source with the spectrophotometer probe illuminating and measuring at 90° to the plumage. Measurements were standardized to a white standard (WS-1, Ocean Optics), considered >98% reflective from 250 to 1500 nm wavelengths. Spectra are arranged in rows, one line for each species and "patch" on the bird.  Some patches were repeatedly measured which can be inferred from multiple measurements of the same "individual".

## File info
There are separate files from different research groups to keep the file sizes relatively small for uploading. Each file contains metadata with information on species names and taxonomy, catalog informatiion where available and raw spectra (percent reflectance from 300 to 700 nm in 2 nm bins).  

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


## Funding
This work was supported by NSF DEB-0215560 to POD and LAW, and by a NSF graduate research fellowship to JKA.



