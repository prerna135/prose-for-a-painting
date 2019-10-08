# Prose for a Painting

Painting captions are often dry and simplistic which motivates us to describe a painting creatively in the style ofShakespearean prose. This is a difficult problem, since there does not exist a large supervised dataset from paintings to Shakespearean prose.  Our solution is to use an intermediate English poem description of the painting and then apply language style transfer which results in Shakespearean prose describing the painting.

## Setup

All instructions for downloading prerequisites can be found in the jupyter notebook.

## Running the notebook

Please download, extract and place the following folders in working directory before running the notebook. These folders contain additional code and data for running the notebook.

```bash
git clone https://github.com/researchmm/img2poem
git clone https://github.com/harsh19/Shakespearizing-Modern-English
```

## Downloading the models

[img2poem model](https://www.dropbox.com/s/2y0mn7a48b56btx/img2poem_model.zip?dl=0): Please download, extract and place under img2poem/code

[text style transfer model](https://www.dropbox.com/s/fk0yse63vz2wybe/shakespeare_model.zip?dl=0)
Please download, extract and place under Shakespearizing-Modern-English/code/models

## Citations
```
@article{kashyap2019proseforapainting,
  title={Prose for a Painting},
  author={Kashyap, Prerna and Phatale, Samrat and Drori, Iddo},
  journal={ICCV Workshop on Closing the Loop Between Vision and Language, 2019},
  year={2019}
}
```
