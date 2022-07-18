# DMix: Adaptive Distance-aware Interpolative Mixup
(ACL 2022 Main conference)

Link to the paper - https://aclanthology.org/2022.acl-short.67/

## Instructions for setting up: <br>
- Install the required packages using requirements.txt <br>
- Replace the Dataset PATH to where it is stored locally. <br>
- Replace the Probability Matrix to the place where it is locally stored. <br>
- Set the threshold values. <br>
- Change bert-base-uncased to bert-base-multilingual-uncased incase running for languages other than english. <br>
- Replace the num_label with the number of labels in the dataset <br>
- Number of training samples in the dataframe <br>
- We have used some standard GLUE Datasets that could be downloaded using the transformer dataset or their official webpage. <br>

*For calculating the Matrix, run the code given in matrix.py. <br>

The code is well documented for further explanation.

## How to Cite

```bibtex
@inproceedings{sawhney-etal-2022-dmix,
    title = "{DM}ix: Adaptive Distance-aware Interpolative Mixup",
    author = "Sawhney, Ramit  and
      Thakkar, Megh  and
      Pandit, Shrey  and
      Soun, Ritesh  and
      Jin, Di  and
      Yang, Diyi  and
      Flek, Lucie",
    booktitle = "Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers)",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.acl-short.67",
    doi = "10.18653/v1/2022.acl-short.67",
    pages = "606--612",
    abstract = "Interpolation-based regularisation methods such as Mixup, which generate virtual training samples, have proven to be effective for various tasks and modalities.We extend Mixup and propose DMix, an adaptive distance-aware interpolative Mixup that selects samples based on their diversity in the embedding space. DMix leverages the hyperbolic space as a similarity measure among input samples for a richer encoded representation.DMix achieves state-of-the-art results on sentence classification over existing data augmentation methods on 8 benchmark datasets across English, Arabic, Turkish, and Hindi languages while achieving benchmark F1 scores in 3 times less number of iterations.We probe the effectiveness of DMix in conjunction with various similarity measures and qualitatively analyze the different components.DMix being generalizable, can be applied to various tasks, models and modalities.",
}
```
