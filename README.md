[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

# Create TF feature betacode

This repository contains the [Jupyter Notebook](Feature_creation_betacode_for_N1904-TF_dataset.ipynb) used to create a new Text-Fabric feature [betacode](https://github.com/tonyjurg/N1904addons/blob/main/docs/features/betacode.md). The final feature file ([betacode.tf](tf/1.0.0/betacode.tf)) was added to the package available at the [tonyjurg/N1904addons](https://tonyjurg.github.io/N1904addons/) repository.

## About Text-Fabric

The Text-Fabric framework is designed to facilitate the analysis and manipulation of large-scale textual data, particularly in the context of ancient languages and biblical texts. The engine of Text-Fabric is its powerful Python library, which provides a comprehensive set of tools for processing and querying structured text data efficiently. The software package is accessible at [https://github.com/annotation/text-fabric](https://github.com/annotation/text-fabric).

## Documentation

Background information on betacode can be found in the following resources:

 - [Beta Code encoding](https://stephanus.tlg.uci.edu/encoding.php)

 - [Quick: TLG Beta Code Quick Reference Guide (pdf)](https://stephanus.tlg.uci.edu/encoding/quickbeta.pdf)

 - [Full: The TLG Beta Code Manual (PDF)](https://stephanus.tlg.uci.edu/encoding/BCM.pdf)

## Attribution and footnotes

The Greek base text is from Nestle1904 Greek New Testament, edited by Eberhard Nestle, published in 1904 by the British and Foreign Bible Society:
> Nestle, Eberhard. Η Καινή Διαθήκη Novum Testamentum Graece (New York: Fleming H. Revell Company, 1904).
The 1913 reprint is available [here](https://archive.org/details/hkainediathekete00lond/), which was transcribed by [Diego Santos](https://sites.google.com/site/nestle1904/home). All this material is in Public domain.

Beta‑Code syntax follows the TLG/Perseus convention: [Thesaurus Linguae Graecae® / Perseus Project spec.](https://stephanus.tlg.uci.edu/encoding/BCM.pdf)

The conversion code between Unicode and Betacode is available at [GitHub repository perseids-tools/beta-code-py](https://github.com/perseids-tools/beta-code-py). This library was made available under the [MIT license](https://github.com/perseids-tools/beta-code-py?tab=MIT-1-ov-file).

The [N1904-TF dataset](https://centerblc.github.io/N1904/) available under [MIT license](https://github.com/CenterBLC/N1904/blob/main/LICENSE.md). Formal reference: 
> Tony Jurg, Saulo de Oliveira Cantanhêde, & Oliver Glanz. (2024). *CenterBLC/N1904: Nestle 1904 Text-Fabric data*. Zenodo. DOI: [10.5281/zenodo.13117911](https://doi.org/10.5281/zenodo.13117910).

## License

The added betacode feature and this notebook are released under the [MIT License, Copyright © 2025 Tony Jurg](https://github.com/tonyjurg/create_TF_feature_betacode/blob/main/LICENSE.md)

## Citation

If you use this repository in your academic work, please [cite it](CITATION.cff).

