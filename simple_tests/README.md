
Create a conda (or virtualenv) environment:

```bash
conda create -n qiskit14ser python=3.11
conda activate qiskit14ser
```

Install the `rustup` tool: [https://rustup.rs/](https://rustup.rs/)

Install the local Qiskit version from source:

```bash
pip install .
```

Test serialization using this custom Qiskit build, and make additional changes to this Qiskit 1.4 version if necessary and redo the installation from source.