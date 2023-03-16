---
title: "Similarity Search of Low Surface Brightness Galaxies in Large Astronomical Catalogs"
collection: publications
permalink: /publication/paper-title-number-4
excerpt: 'Paper detailing lsh_astro, a tool that uses Locality-Sensitive Hashing with PySpark to perform an approximate similarity search of Low Surface Brightness Galaxies (LSBGs) in large astronomical catalogs. It allows for a quick and computationally efficient way for astronomers to find new LSBG candidates in large astronomical catalogs needing only one labeled LSBG.'
date: 2022-01-01
venue: 'NeurIPS: LatinX in AI Research Workshop'
paperurl: 'https://doi.org/10.52591/lxai202211282'
citation: 'Similarity Search of Low Surface Brightness Galaxies in Large Astronomical Catalogs. Marcos Tidball, Cristina Furlanetto. Neural Information Processing Systems (NeurIPS)
Conference: LatinX in AI (LXAI) Research Workshop, 2022.'

---
Low Surface Brightness Galaxies (LSBGs) constitute an important segment of the galaxy population, however, due to their diffuse nature, their search is challenging. The detection of LSBGs is usually done with a combination of parametric methods and visual inspection, which becomes unfeasible for future astronomical surveys that will collect petabytes of data. Thus, in this work we explore the usage of Locality-Sensitive Hashing for the approximate similarity search of LSBGs in large astronomical catalogs. We use 11670190 objects from the Dark Energy Survey Y3 Gold coadd catalog to create an approximate k nearest neighbors model based on the properties of the objects, developing a tool able to find new LSBG candidates while using only one known LSBG. From just one labeled example we are able to find various known LSBGs and many objects visually similar to LSBGs but not yet catalogued. Also, due to the generality of similarity search models, we are able to search for and recover other rare astronomical objects without the need of retraining or generating a large sample. Our code is available on [https://github.com/zysymu/lsh-astro](https://github.com/zysymu/lsh-astro).
