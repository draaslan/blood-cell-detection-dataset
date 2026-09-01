# Blood Cell Detection Dataset

[![DOI](https://img.shields.io/badge/DOI-10.57967%2Fhf%2F10256-blue)](https://doi.org/10.57967/hf/10256)

## Introduction

This dataset contains annotated red blood cells(RBC) and white blood cells(WBC) from peripheral blood smear taken from a light microscope.

![Blood Cell Detection Dataset](https://user-images.githubusercontent.com/3878466/80433866-dd0f6380-8900-11ea-8018-ecd4e8a7afe8.png)

> **If you use this dataset in your research, please cite it.** See the [Citation](#citation) section below for the correct reference. Please do not cite the auto-generated Hugging Face reference, as it lists an incorrect title and year.

## About Blood Cell Detection Dataset

- Images are collected from peripheral blood smear slides on a light microscope with high magnification and resolution.
- It contains 100 annotated images with labeled **RBC as 2237** and **WBC as 103**.
- Every image contains RGB channels and also is 256 pixels in both height and width.
- **images** folder contains image files as a png format. **annotations.csv** file contains both locations and labels.
- The total dataset file size is approximately 14MB.
- All PRs are welcome.

## What is Peripheral Blood Smear?

A peripheral blood smear is a thin layer of blood smeared on a glass microscope slide and then stained in such a way as to allow the various blood cells to be examined microscopically. Blood films are examined in the investigation of hematological (blood) disorders and are routinely employed to look for blood parasites, such as those of malaria and filariasis. ([Wikipedia](https://en.wikipedia.org/wiki/Blood_film))

Examination of the peripheral blood smear is an inexpensive but powerful diagnostic tool in both children and adults. In some ways it is becoming a "lost art" but it often provides rapid, reliable access to information about a variety of hematologic disorders. The smear offers a window into the functional status of the bone marrow, the factory producing all blood elements. It is particularly important when assessing cytopenic states (eg, anemia, leukopenia, thrombocytopenia). Review of the smear is an important adjunct to other clinical data; in some cases, the peripheral smear alone is sufficient to establish a diagnosis. ([UpToDate](https://www.uptodate.com/contents/evaluation-of-the-peripheral-blood-smear))

## Other Sources

This dataset is also available at:

- Hugging Face: https://huggingface.co/datasets/draaslan/blood-cell-detection
- Kaggle: https://www.kaggle.com/datasets/draaslan/blood-cell-detection-dataset

All three are the same dataset. Please use the citation below regardless of the source you obtained it from.

## Citation

**BibTeX**

```bibtex
@misc{aslan2020bcdd,
  author    = {Aslan, A.},
  title     = {WBC \& RBC detection dataset from peripheral blood smears},
  year      = {2020},
  publisher = {Hugging Face},
  doi       = {10.57967/hf/10256},
  url       = {https://github.com/draaslan/blood-cell-detection-dataset}
}
```

**APA**

Aslan, A. (2020). *WBC & RBC detection dataset from peripheral blood smears* [Data set]. https://doi.org/10.57967/hf/10256

**Vancouver**

Aslan A. WBC & RBC detection dataset from peripheral blood smears [Internet]. 2020. Available from: https://doi.org/10.57967/hf/10256

**Author ORCID:** [0000-0001-8226-8462](https://orcid.org/0000-0001-8226-8462)

## Licence

See LICENSE for details.
