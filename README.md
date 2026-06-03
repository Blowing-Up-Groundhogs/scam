# SCAM — A Text Recognition Dataset from Sahidic Coptic Ancient Manuscripts

Project page for the ICDAR 2026 paper introducing **SCAM (Sahidic Coptic Ancient
Manuscripts)**, a line-level Handwritten Text Recognition (HTR) dataset built from
the 11th-century *CLM 359* manuscript.

🔗 **Live page:** https://scam.silviacascianelli.com

## About the dataset

- **3,240** line-level samples (53 pages, 27 leaves) from a single-author manuscript
  written in the extinct **Sahidic Coptic** dialect, in *scriptio continua*.
- **99** graphemes, diplomatically transcribed by an expert Coptologist.
- A **dual-archive design** — `SCAM-A` (professional scans) and `SCAM-B` (camera
  photographs) — that exposes a realistic cross-domain gap.
- A benchmark of **11 state-of-the-art HTR models** across CTC, attention, and
  Transformer paradigms.

## Development

This is a static site (HTML + CSS, Bulma via CDN). To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Deployed via GitHub Pages; the custom domain is set in `CNAME`.

## Structure

```
index.html              # the project page
static/css/index.css    # theme & layout
static/images/          # figures cropped from the paper
CNAME                   # custom domain for GitHub Pages
```

## Citation

```bibtex
@inproceedings{quattrini2026scam,
  title     = {A Text Recognition Dataset from Sahidic Coptic Ancient Manuscripts},
  author    = {Quattrini, Fabio and Zaccagnino, Carmine and Bianchi, Costanza
               and Cascianelli, Silvia and Cucchiara, Rita},
  booktitle = {International Conference on Document Analysis and Recognition (ICDAR)},
  year      = {2026}
}
```
