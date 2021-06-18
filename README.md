## Some commands

$ pip install -U jupyter-book

$ git clone https://github.com/kthpanor/echem.git

$ cd echem

$ vi docs/dft.md

$ jupyter-book build .

$ open open _build/html/index.html


## Creating final html-version

$ ghp-import -n -p -f _build/html

This requires installing ghp-import

## Distribution of labour

1. Tutorials and Workflows: TF will get started on this section by setting up a few tutorials on spectroscopy (UV/vis, X-ray);

2. Electronic Structure Theory:
  -  Hartree—Fock theory: PN will move Ch. 4 from overleaf here;
  -  Density functional theory: ZR will move Ch. 5 from overleaf here; will include also a jupyter notebook example for Slater exchange;
  -  Wave-function theory: MD is main responsible and will set up this section (Ch. 6 overleaf); ZR will contribute with “Second quantization”;
  -  Configuration interaction: MD

3. Potential Energy Surfaces: IB is responsible for this section; will contact ML and MA to ask if they wish/can contribute to the respective subsections;
  -  Molecular structure optimization: IB (Ch. 13 overleaf)
  -  Transition-state theory: MA (Ch. 14 overleaf)
  -  Conical intersections: MA (Ch. 15 overleaf)

4. Molecular dynamics: ML (Ch. 7 overleaf)

5. Properties:
  - Response theory: PN (Ch. 8 overleaf)
  - Algebraic diagrammatic construction: IB (Ch. 10 overleaf)
  - Exciton coupling model: XL (Ch. 11 overleaf)

6. Environment: OV will take main responsibility for this section and will move Ch. 12 from overleaf here, as well as add material on loprop.
