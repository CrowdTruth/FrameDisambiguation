# Frame Disambiguation with CrowdTruth

Crowdsourced dataset of 433 sentence-word pairs from the [FrameNet corpus v1.7](https://framenet.icsi.berkeley.edu/), annotated for frame disambiguation.

The corpus has been referenced in the following paper:

* Anca Dumitrache, Lora Aroyo and Chris Welty: **[Capturing and Interpreting Ambiguity in Crowdsourcing Frame Disambiguation](https://arxiv.org/abs/1805.00270)**. [HCOMP 2018](https://www.humancomputation.com/2018/).

To replicate the data processing from the paper, use the Jupyter Notebook file `CrowdTruth metrics.ipynb`. It requires the installation of the [CrowdTruth metrics](https://github.com/CrowdTruth/CrowdTruth-core) Python package (v >= 2.0).

The data aggregated with CrowdTruth metrics is available in folder `data/output/`

The raw crowdsourcing data is available in folder `data/input/`

If you find this data useful in your research, please consider citing:

```
@inproceedings{dumitrache2018frames,
  Author = {Anca Dumitrache and Lora Aroyo and Chris Welty},
  Title = {Capturing Ambiguity in Crowdsourcing Frame Disambiguation},
  Booktitle = {The sixth AAAI Conference on Human Computation and Crowdsourcing},
  Year = {2018}
}
```