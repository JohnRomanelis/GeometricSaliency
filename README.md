# Geometric Saliency

This jupyter notebook is designed to assist students who are either new to Python or the fild of Computetional Geometry and Geometry Processing. The goal is to provide a practical and hands-on approach to undestand basic principles by implementing a straightforward yet useful algorithm. 

 
<br/><br/>
<div align="center">
    <img src = "./resources/img/saliency_vis.png", width = 420, aligh=center />
</div>
<br/><br/>

## Requirements

I tried this with the following setup. Note that choosing different versions may not work as Open3D is still an experimental library.

```
open3d==0.17.0
torch==1.13.1 + cuda==11.6
numpy=1.24.0
tensorboard==2.14.1
```

## Acknowledgements
```
@ARTICLE{9120202,
  author={Arvanitis, Gerasimos and Lalos, Aris S. and Moustakas, Konstantinos},
  journal={IEEE Transactions on Industrial Informatics}, 
  title={Robust and Fast 3-D Saliency Mapping for Industrial Modeling Applications}, 
  year={2021},
  volume={17},
  number={2},
  pages={1307-1317},
  doi={10.1109/TII.2020.3003455}}
```
```
@inproceedings {10.2312:3dor.20201160,
booktitle = {Eurographics Workshop on 3D Object Retrieval},
editor = {Schreck, Tobias and Theoharis, Theoharis and Pratikakis, Ioannis and Spagnuolo, Michela and Veltkamp, Remco C.},
title = {{Fast Feature Curve Extraction for Similarity Estimation of 3D Meshes}},
author = {Romanelis, Ioannis and Arvanitis, Gerasimos and Moustakas, Konstantinos},
year = {2020},
publisher = {The Eurographics Association},
ISSN = {1997-0471},
ISBN = {978-3-03868-126-7},
DOI = {10.2312/3dor.20201160}
}
```
