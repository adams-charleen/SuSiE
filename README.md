# SusieR (without coloc) for PTER 

I tried this out and am puzzled by the results. 

## Fine-mapping tools for multiple ancestry

### MultiSuSiE

[Price Lab - MultiSuSiE Preprint](https://www.medrxiv.org/content/10.1101/2024.05.13.24307291v1.full.pdf)

Uses All of Us

```bash
git clone https://github.com/jordanero/MultiSuSiE
cd MultiSuSiE
conda env create -f environment.yml
conda activate MultiSuSiE
pip install . -U

git clone https://github.com/jordanero/MultiSuSiE
cd MultiSuSiE
pip install . -U
```

### SuShiE

[Mancuso lab - SuShiE Preprint](https://www.medrxiv.org/content/10.1101/2024.04.15.24305836v1)

Uses TopMed MESA

```bash
git clone https://github.com/mancusolab/sushie.git
cd sushie
pip install .
```

They have other potentially relevant [software](https://www.mancusolab.com/software).
