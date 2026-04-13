# Qiskit Learning

A personal project for learning quantum computing with Qiskit.

## Structure

```
├── coding_with_qiskit/      # Notebooks from the "Coding with Qiskit" tutorial series
└── from_zero_to_quantum/    # Notebooks from the "From Zero to Quantum" tutorial series
```

## Setup

This project uses a Conda environment. To create and activate it:

```bash
conda env create -f coding_with_qiskit/environment_qiskit.yml
conda activate cwq
```

Then launch JupyterLab:

```bash
jupyter lab
```

## Key Dependencies

- `qiskit` — core quantum computing framework
- `qiskit-aer` — local simulators
- `qiskit-ibm-runtime` — run circuits on real IBM quantum hardware
- `matplotlib` — circuit and result visualization
- `python-dotenv` — manage IBM credentials via `.env`
