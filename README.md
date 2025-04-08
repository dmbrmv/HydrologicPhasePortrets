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
├── src                    # Main Python modules and scripts
│   ├── DataProcessing     # Data ingestion, cleaning, and SSA/CCM analysis scripts
│   └── Plotting           # Visualization and plotting utilities
├── pyproject.toml         # Python project dependencies (Poetry)
├── poetry.lock            # Locked Python dependencies
└── README.md              # Project documentation
```

---

## 🛠️ Installation and Setup

This project uses **[Poetry](https://python-poetry.org/)** for dependency management.

git clone the repository: https://github.com/dmbrmv/HydrologicPhasePortrets

```bash
git clone https://github.com/dmbrmv/HydrologicPhasePortrets.git
cd HydrologicPhasePortrets
```

### Prerequisites

Install Poetry if you haven't already:

```bash
pip install poetry
```

Install the project dependencies:

```bash
poetry install
```

or if you have Poetry installed, you can use the following command to install the dependencies:

```bash
poetry install --no-root
```

This will create a virtual environment and install all the required packages.
Activate the virtual environment:

```bash
eval $(poetry env activate)
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
