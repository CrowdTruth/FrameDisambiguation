# Frame Disambiguation with CrowdTruth

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1472345.svg)](https://doi.org/10.5281/zenodo.1472345)

This repository contains a ground truth corpus for semantic frame disambiguation, acquired with crowdsourcing and processed with **[CrowdTruth](http://crowdtruth.org/)** metrics that capture ambiguity in annotations by measuring inter-annotator disagreement.

The dataset contains annotations for 433 sentence-word pairs from the [FrameNet corpus v.1.7](https://framenet.icsi.berkeley.edu/), with each sentence-word pair annotated for frame disambiguation by 15 workers. The crowdsourced data was collected from [Amazon Mechanical Turk](https://www.mturk.com/).

The corpus has been referenced in the following papers:

* Anca Dumitrache, Lora Aroyo and Chris Welty: **A Crowdsourced Frame Disambiguation Corpus with Ambiguity**. [NAACL 2019](https://naacl2019.org/) (in publication).
* Anca Dumitrache, Lora Aroyo and Chris Welty: **[Capturing and Interpreting Ambiguity in Crowdsourcing Frame Disambiguation](https://arxiv.org/abs/1805.00270)**. [HCOMP 2018](https://www.humancomputation.com/2018/).

To replicate the data processing from the paper, use the Jupyter Notebook file `CrowdTruth metrics.ipynb`. It requires the installation of the [CrowdTruth metrics](https://github.com/CrowdTruth/CrowdTruth-core) Python package (v >= 2.0).

The data aggregated with CrowdTruth metrics is available in folder `data/output/`

The raw crowdsourcing data is available in folder `data/input/`

If you find this data useful in your research, please consider citing:

```
@inproceedings{dumitrache2018frames,
  Author = {Anca Dumitrache and Lora Aroyo and Chris Welty},
  Title = {A Crowdsourced Frame Disambiguation Corpus with Ambiguity},
  Booktitle = {Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL)},
  Year = {2019}
}
```
