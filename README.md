# MetalDAM

MetalDAM is a metallography dataset from additive manufacturing of steels. All images were kindly provided by ArcelorMittal engineers. 

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

If you want to cite MetalDAM, please use the following citation:

~~~latex
@misc{metaldam,
  title={MetalDAM: Metallography dataset from additive manufacturing},
  author={{ArcelorMittal} and {DaSCI Andalusian Research Institute}},
  url={https://github.com/ari-dasci/OD-MetalDAM}
}
~~~

A publication presenting the dataset will be added here soon.
