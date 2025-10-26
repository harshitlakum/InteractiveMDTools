# InteractiveMDTools

InteractiveMDTools is a small collection of Python-based tools to explore basic molecular dynamics concepts. It includes visualizations of **bond potentials** and simple **MD simulations** using the **ASE** library. All simulations run in Jupyter notebooks with interactive widgets.

---

## Features

* **Morse Potential**

  * Adjustable parameters: dissociation energy (D), equilibrium bond distance (r_0), stiffness (\alpha)
  * Visualize realistic bond stretching

* **Harmonic Bond Potential**

  * Adjustable spring constant (k)
  * Compare harmonic vs anharmonic behavior

* **Basic Molecular Dynamics (MD)**

  * Simple MD setup with ASE
  * Time evolution of a molecular system

* **Energy Tracking**

  * Plot potential, kinetic, and total energy during simulations

---

## Installation

```bash
pip install numpy matplotlib ase ipywidgets
```

Enable widgets in Jupyter if needed:

```bash
jupyter nbextension enable --py widgetsnbextension
```

---

## Usage

```bash
git clone https://github.com/your-username/InteractiveMDTools.git
cd InteractiveMDTools
jupyter notebook
```

Open any notebook and adjust the parameters interactively.

---

## Requirements

* Python 3.7 or later
* Jupyter Notebook
* ASE (Atomic Simulation Environment)
* NumPy, Matplotlib, ipywidgets

---

## License

MIT License

