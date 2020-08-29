# A Linkage Pipeline for Place Records Using Multi-view Encoders

Extracting information about Web entities has become commonplace in the academy and industry alike. In particular, data about places distinguish themselves as rich sources of geolocalized information and spatial context, serving as a foundation for a series of applications. These entities, however, are inherently noisy and introduce several normalization problems, which need to be tackled in order to obtain a clean database. Record linkage, also known as entity resolution, refers to the detection of replicated data from potentially multiple sources, and is one of the most critical cleaning processes to be conducted in a database. This work presents a novel record linkage solution for large scale Web-based places data, being composed of three steps: generation of potential duplicate place pairs, place pair deduplication, and clusterization of the classification results. The detection of duplicate places is the solution's core, being a complex and seldom approached problem in this domain. Hence, the main contribution of this work is in the form of a model based on a deep neural network architecture, which utilizes encoders for different information levels of names, addresses, geographical coordinates, and categories. Each encoder uses distinct structures to generate representation vectors, which are concatenated, compared, and transported to a feature space that represents duplications and non-duplications. Additionally, this work proposes alternative classification models for real time usage by means of APIs. The complete solution is analyzed, with the classification model for place pairs being evaluated on top of two distinct data sets and compared against the state-of-the-art. As a result, the proposed solution is shown to handle large quantities of data in a production environment, and the classification model outperforms the baselines in both data sets, thus constituting a complete and efficient solution for the record linkage problem in the places data domain.

## About The Repository

This repository holds the latest version of a MSc thesis named `A Linkage Pipeline for Place Records Using Multi-view Encoders` which proposes a linkage pipeline and a novel deep neural network for pairwise place matching named `PlacERN` as the main driver behind said pipeline.

## Citing

Citations can be made as such:

```
@mastersthesis{cousseau-thesis:2020,
  author = {Vinicius Cousseau},
  title = {A Linkage Pipeline for Place Records Using Multi-view Encoders},
  school = {Universidade Federal de Pernambuco (UFPE), Pernambuco, Brazil},
  year = {2020},
  url = "https://github.com/vinimoraesrc/placern"
}

```

## Associated Publications

V. Cousseau, L. Barbosa, [*Industrial paper: Large-scale record linkage of web-based place entities*](https://sol.sbc.org.br/index.php/sbbd/article/view/8820)

```
@inproceedings{cousseau-linkage:2019
 author = {Vinícius Cousseau and Luciano Barbosa},
 title = {Industrial Paper: Large-scale Record Linkage of Web-based Place Entities},
 booktitle = {Anais Principais do XXXIV Simpósio Brasileiro de Banco de Dados},
 location = {Fortaleza},
 year = {2019},
 keywords = {},
 issn = {0000-0000},
 pages = {181--186},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/sbbd.2019.8820},
 url = {https://sol.sbc.org.br/index.php/sbbd/article/view/8820}
}
```
