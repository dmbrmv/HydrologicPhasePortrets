# Hydrological Dynamic Clustering: SSA and CCM Analysis

This repository contains the source code, data processing scripts, notebooks, and LaTeX source files accompanying our research on **Identifying Dynamically Similar Hydrological Systems using Singular Spectrum Analysis (SSA) and Convergent Cross Mapping (CCM)**.

---

## 📁 Repository Structure

```
.
├── images                 # Figures and visualizations
├── notebooks              # Jupyter notebooks and preliminary tests
│   ├── InitialBook.ipynb
│   └── test.py
├── PaperText              # LaTeX source and compiled PDF of the publication
│   ├── references.bib
│   ├── TextBody.aux
│   ├── TextBody.bbl
│   ├── TextBody.blg
│   ├── TextBody.fdb_latexmk
│   ├── TextBody.fls
│   ├── TextBody.log
│   ├── TextBody.out
│   ├── TextBody.pdf
│   ├── TextBody.synctex.gz
│   └── TextBody.tex
├── src                    # Main Python modules and scripts
│   ├── DataProcessing     # Data ingestion, cleaning, and SSA/CCM analysis scripts
│   │   └── some_file.py
│   └── Plotting           # Visualization and plotting utilities
├── pyproject.toml         # Python project dependencies (Poetry)
├── poetry.lock            # Locked Python dependencies
└── README.md              # Project documentation
```

---

## 🛠️ Installation and Setup

This project uses **[Poetry](https://python-poetry.org/)** for dependency management.

1. Install dependencies:

```bash
poetry install
```

2. Activate the environment:

```bash
poetry shell
```

---

## 🚀 Usage

### Data Processing

Scripts for data processing, SSA and CCM analyses are located in:

- `src/DataProcessing/`

Run an example script:

```bash
python src/DataProcessing/some_file.py
```

### Notebooks

Jupyter notebooks for exploration and visualization:

- `notebooks/InitialBook.ipynb`

To open:

```bash
jupyter notebook notebooks/InitialBook.ipynb
```

---

## 📄 Paper Compilation

The paper is written in LaTeX and found in the `PaperText/` directory.

To compile:

```bash
cd PaperText
pdflatex TextBody.tex
bibtex TextBody
pdflatex TextBody.tex
pdflatex TextBody.tex
```

The compiled PDF will be available as: [`TextBody.pdf`](PaperText/TextBody.pdf)

---

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Create a Pull Request

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

For questions or collaboration inquiries, reach out:

- **Your Name** — [your.email@example.com](mailto:your.email@example.com)  
- **Institution** — Your Institution Name

---

**Enjoy exploring hydrological dynamics!** 🌊📈
