# Screen Content Dataset (PolyUSCC)

## 1. Introduction

PolyUSCC is a screen content (SC) video dataset for research on screen content coding and quality enhancement. This release contains **20 video sequences**, organized into **13 training sequences** and **7 validation sequences**. The collection includes self-captured videos and sequences from JCT-VC [1] and Tsang et al. [2].

Additional screen content videos are available in [PolyUSCCv2](https://github.com/HUANGZiyin1/PolyUSCCv2).

## 2. Sequence Dataset

The following lists provide the resolution and frame count of each video.

### Training Set (13 Sequences)

| Sequence | Resolution | Frames |
|---|---:|---:|
| `PolyuEIEweb1` | 1920 × 1080 | 100 |
| `Polyuwebcmdvideo2` | 1920 × 1080 | 100 |
| `Polyuwebvideo1` | 1920 × 1080 | 100 |
| `NewsBrowse` | 1680 × 1050 | 100 |
| `PaperPdf` | 1680 × 1050 | 100 |
| `VisualStudio` | 1680 × 1050 | 100 |
| `scWeb` | 1280 × 720 | 500 |
| `sccadwaveform` | 1920 × 1080 | 200 |
| `scdoc` | 1280 × 720 | 500 |
| `scpcblayout` | 1920 × 1080 | 200 |
| `scpptdocxls` | 1920 × 1080 | 200 |
| `scvideoconferencingdocsharing` | 1280 × 720 | 300 |
| `MsStore` | 1680 × 1050 | 100 |

### Validation Set (7 Sequences)

| Sequence | Resolution | Frames |
|---|---:|---:|
| `BigBuck` | 1920 × 1080 | 404 |
| `EnglishDocumentEditing` | 1920 × 1080 | 300 |
| `KimonoError1` | 2560 × 1440 | 1006 |
| `MissionControlClip1` | 2560 × 1440 | 601 |
| `scviking` | 1280 × 720 | 300 |
| `consolenew2` | 1920 × 1080 | 300 |
| `YouTube` | 1680 × 1050 | 100 |

## 3. Download

Download the dataset from [Google Drive](https://drive.google.com/file/d/1_QblUlM4WDEmYl6OSlNlCWk0T8rkvMhw/view?usp=drive_link).

## 4. References

- [1] JCT-VC. *Screen Content Sequences Provided by JCT-VC*. Available: ftp://mpeg.tnt.uni-hannover.de/testsequences/
- [2] S.-H. Tsang, Y.-L. Chan, and W. Kuang, “Mode Skipping for HEVC Screen Content Coding via Random Forest,” *IEEE Transactions on Multimedia*, vol. 21, no. 10, pp. 2433–2446, Oct. 2019. DOI: [10.1109/TMM.2019.2907472](https://doi.org/10.1109/TMM.2019.2907472).
- [3] Z. Huang, Y.-L. Chan, S.-H. Tsang, and K.-M. Lam, “Mode Information Guided CNN for Quality Enhancement of Screen Content Coding,” *IEEE Access*, vol. 11, pp. 24149–24161, 2023. DOI: [10.1109/ACCESS.2023.3242673](https://doi.org/10.1109/ACCESS.2023.3242673). [PDF](https://ieeexplore.ieee.org/iel7/6287639/10005208/10038539.pdf).

## 5. Citation

If you use the **PolyUSCC** dataset in your research, please cite **all three references [1]–[3]** to acknowledge the source sequences and the associated research. BibTeX entries are provided below.

### JCT-VC Source Sequences [1]

```bibtex
@misc{jctvc_screen_content_sequences,
  author = {{JCT-VC}},
  title  = {Screen Content Sequences Provided by {JCT-VC}},
  url    = {ftp://mpeg.tnt.uni-hannover.de/testsequences/}
}
```

### Random Forest Mode Skipping [2]

```bibtex
@article{tsang2019mode,
  author  = {Tsang, Sik-Ho and Chan, Yui-Lam and Kuang, Wei},
  title   = {Mode Skipping for {HEVC} Screen Content Coding via Random Forest},
  journal = {IEEE Transactions on Multimedia},
  volume  = {21},
  number  = {10},
  pages   = {2433--2446},
  year    = {2019},
  month   = oct,
  doi     = {10.1109/TMM.2019.2907472},
  url     = {https://doi.org/10.1109/TMM.2019.2907472}
}
```

### Mode Information Guided CNN [3]

```bibtex
@article{huang2023mode,
  author  = {Huang, Ziyin and Chan, Yui-Lam and Tsang, Sik-Ho and Lam, Kin-Man},
  title   = {Mode Information Guided {CNN} for Quality Enhancement of Screen Content Coding},
  journal = {IEEE Access},
  volume  = {11},
  pages   = {24149--24161},
  year    = {2023},
  doi     = {10.1109/ACCESS.2023.3242673},
  url     = {https://doi.org/10.1109/ACCESS.2023.3242673}
}
```
