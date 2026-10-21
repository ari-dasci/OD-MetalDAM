# MetalDAM

MetalDAM is a metallography dataset from additive manufacturing of steels. All images were kindly provided by ArcelorMittal engineers.

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

|Dataset|Images|Download|Cite|
|:-|:-|:-|:-|
|[Labeled](#labeled-dataset)|42|[&darr; Download](https://github.com/ari-dasci/OD-MetalDAM/releases)|[Citation](#associated-publication)|
|[Unlabeled](#unlabeled-dataset)|164|[&darr; Download](https://github.com/ari-dasci/OD-MetalDAM/releases)|[Citation](#associated-publication)|

## Labeled dataset

The labeled set contains 42 grayscale images taken with a scanning electron microscope, with resolutions 1280x895 and 1024x703 (after cropping the information band at the bottom).

| Label | Frequency |
|:-|-:|
|0. Matrix|31.86%|
|1. Austenite|58.26%|
|2. Martensite/Austenite|8.96%|
|3. Precipitate*|0.24%|
|4. Defect|0.68%|

(*) The  reduced  size of  the  precipitates  increased  notably  the  effort  of  annotating  these  micro-constituents, so most of them were ignored during the annotation process.

## Unlabeled dataset

An additional set of 164 images obtained from the same materials is available as well.

## Acknowledgments

This dataset has been generated and provided by ArcelorMittal Global R&D. Special thanks to the researchers Margarita Guerrero Gesto, Rosalía Rementeria Fernández and Laura del Río Fernandez.

## Publications and citations

If you use MetalDAM, please cite the paper that presents it:

~~~latex
@article{luengo2022metaldam,
  title     = {A tutorial on the segmentation of metallographic images:
               Taxonomy, new {MetalDAM} dataset, deep learning-based ensemble
               model, experimental analysis and challenges},
  author    = {Luengo, Juli{\'a}n and Moreno, Ra{\'u}l and Sevillano, Iv{\'a}n and
               Charte, David and Pel{\'a}ez-Vegas, Adri{\'a}n and
               Fern{\'a}ndez-Moreno, Marta and Mesejo, Pablo and Herrera, Francisco},
  journal   = {Information Fusion},
  volume    = {78},
  pages     = {232--253},
  year      = {2022},
  doi       = {10.1016/j.inffus.2021.09.018}
}
~~~

To reference the dataset itself, you can additionally use:

~~~latex
@misc{metaldam,
  title={MetalDAM: Metallography dataset from additive manufacturing},
  author={{ArcelorMittal} and {DaSCI Andalusian Research Institute}},
  url={https://github.com/ari-dasci/OD-MetalDAM}
}
~~~

Both entries share the same license terms (see [License](#license)).

## License

The MetalDAM images (provided by ArcelorMittal Global R&D) and the annotations produced by
DaSCI are distributed under the
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License][cc-by-nc-nd],
the same license as the associated publication.

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: https://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png

You are free to copy and redistribute the material in any medium or format, provided that you:

- give appropriate credit to ArcelorMittal Global R&D and DaSCI, link to the license, and
  indicate if changes were made;
- do not use the material for commercial purposes;
- do not distribute modified versions of the dataset.

Using the images to train, validate or evaluate models, and reporting derived aggregate
results in a scientific publication, are uses permitted by this license. If you need terms
beyond these, please contact the authors.
