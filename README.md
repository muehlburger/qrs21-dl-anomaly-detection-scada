[![DOI](https://zenodo.org/badge/400414721.svg)](https://zenodo.org/badge/latestdoi/400414721)

# Code for our paper

This repository contains the code for our paper *"On the Effects of Data Sampling for Deep Learning on Highly Imbalanced Data from SCADA PowerGrid Substation Networks for Intrusion Detection"*.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install our used libraries.

```bash
pip install -r requirements.txt -v
```

## Usage

You find our implementation in the [Jupyter notebook](code.ipynb).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Citation
If you find our work useful, please cite our paper:

```bibtex 493.5 MB
@inproceedings{wotawaEffectsDataSampling2021,
  title = {On the {{Effects}} of {{Data Sampling}} for {{Deep Learning}} on {{Highly Imbalanced Data}} from {{SCADA Power Grid Substation Networks}} for {{Intrusion Detection}}},
  booktitle = {2021 {{IEEE}} 21st {{International Conference}} on {{Software Quality}}, {{Reliability}} and {{Security}} ({{QRS}})},
  author = {Wotawa, Franz and M{\"u}hlburger, Herbert},
  year = {2021},
  month = dec,
  pages = {864--872},
  issn = {2693-9177},
  doi = {10.1109/QRS54544.2021.00095},
  abstract = {The security of cyber-physical systems is constantly threatened through cyber-attacks using available networking infrastructure. To prevent such attacks, anomaly-based intrusion detection systems are used in practice. Unfortunately, it is considered a hard task to detect the constantly improving attacks without prior knowledge of the attacks themselves. Hence, improved intrusion detection systems are of uttermost importance for preventing successful attacks of our today's network-based infrastructure. In this paper, we focus on improving intrusion detection systems. We build on former work on intrusion detection of power grid substation SCADA network traffic where a real-world data set is available. In contrast to previous work, we take imbalances of data used to learn attack patterns into account. Besides outlining the underlying foundations, the models used, and the experimental setup, we present and discuss the experimental results obtained using the available data set.},
  keywords = {Anomaly Detection,Decision trees,Deep learning,Intrusion detection,Intrusion Detection,Neural networks,Power Grid Substation Networks,Power grids,SCADA network traffic,Substations,Telecommunication traffic}
}


```

## License
[MIT](LICENSE)
