# OneSign: Unifying Sign Language Understanding Tasks with One Model

Official repository for **OneSign**, a unified framework for sign language
understanding.

OneSign reformulates Isolated Sign Language Recognition (ISLR), Continuous Sign
Language Recognition (CSLR), and Sign Language Translation (SLT) under a single
training and inference paradigm. A single model checkpoint supports all tasks
without task- or dataset-specific retraining.

To model the distributional gap between continuous sign representations and
discrete text tokens, OneSign introduces a **Modality-Adaptive
Mixture-of-Experts (MA-MoE)** architecture with an always-activated shared expert
and modality-specific experts for sign and text tokens.

## News

- **2026-08-18:** OneSign preprint released.
- **TODO:** Release code and pretrained models.

## CSL-OpenWorld

We introduce **CSL-OpenWorld**, a large-scale, open-domain Chinese Sign Language
dataset collected from diverse web sources. It contains more than 100K samples
and covers a broad range of topics, signers, backgrounds, and recording
conditions.

- [CSL-OpenWorld pose dataset and access agreement](https://huggingface.co/datasets/hulala/CSL-OpenWorld-pose)
- [SignDataset collection](https://huggingface.co/collections/hulala/signdataset)

Please read and follow the dataset release agreement on Hugging Face before
requesting access or using the data. The dataset must not be redistributed.

## TODO

- [ ] Release training and inference code
- [ ] Release pretrained checkpoints
- [ ] Release data preprocessing instructions
- [ ] Release evaluation scripts

## Citation

If you find OneSign or CSL-OpenWorld useful in your research, please cite:

```bibtex
@article{gan2026onesign,
  title     = {OneSign: Unifying Sign Language Understanding Tasks with One Model},
  author    = {Gan, Shiwei and Yin, Yafeng and Liu, Xiao and Tuerdaken, Desibieer and
               Jiang, Zhiwei and Xie, Lei and Lu, Sanglu},
  year      = {2026},
  publisher = {arXiv}
}
```

## Acknowledgement

This work uses the CSL-OpenWorld dataset collected and curated by Intelligent
Sensing and Visual Computing / Nanjing University.
