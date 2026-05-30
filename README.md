# Quantum Computing Notebooks

Introductory Quantum Computing — Summer School

Hands-on notebooks using [QuTiP](https://qutip.org/) to simulate and verify core quantum algorithms. Each notebook covers one section.

---

## Notebooks

| Notebook | Section | Topics | Open |
|---|---|---|---|
| [nb1_foundations.ipynb](nb1_foundations.ipynb) | §1 | Qubits, gates, Bloch sphere, Bell states, Schmidt decomposition | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb1_foundations.ipynb) |
| [nb2_qft.ipynb](nb2_qft.ipynb) | §2 | QFT product formula, unitarity, approximate QFT truncation error | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb2_qft.ipynb) |
| [nb3_qpe.ipynb](nb3_qpe.ipynb) | §3 | QPE circuit, precision theorem, eigenphase error bound | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb3_qpe.ipynb) |
| [nb4_shor.ipynb](nb4_shor.ipynb) | §4 | Modular-multiplication unitary, Shor pipeline, continued fractions | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb4_shor.ipynb) |
| [nb5_grover.ipynb](nb5_grover.ipynb) | §5 | Grover's algorithm, amplitude estimation via QPE on Grover operator | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb5_grover.ipynb) |
| [nb6_hamsim.ipynb](nb6_hamsim.ipynb) | §6 | Stone's theorem, Trotter/Strang splitting, convergence verification | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb6_hamsim.ipynb) |
| [nb7_hhl.ipynb](nb7_hhl.ipynb) | §7 | HHL step-by-step, controlled rotation, post-selection probability | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb7_hhl.ipynb) |
| [nb8_outlook.ipynb](nb8_outlook.ipynb) | §8 | Continuous-time quantum walk, spreading rate, interference patterns | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/o-tse/quantum-computing/blob/main/notebooks/nb8_outlook.ipynb) |

---

## Prerequisites

- Python 3.9+
- [QuTiP](https://qutip.org/) (`pip install qutip`)
- NumPy, SciPy, Matplotlib (`pip install numpy scipy matplotlib`)
- Jupyter (`pip install jupyter`)

## Running the notebooks

### Locally

```bash
cd notebooks
jupyter notebook
```

### Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Select **File → Open notebook → GitHub**, paste this repository's URL, and open the desired notebook.
3. Install the required packages by running this cell at the top:
   ```python
   !pip install qutip numpy scipy matplotlib
   ```
4. Run all cells with **Runtime → Run all**.

> **Note:** Colab sessions are ephemeral. Any local file changes are lost when the session ends. Use **File → Save a copy in Drive** to keep your work.
