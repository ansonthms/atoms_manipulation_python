# Atomic Manipulation in Python

A comprehensive course on manipulating atoms, molecules, crystals, and surfaces using vanilla Python.

## Prerequisites

- Python 3.8+
- NumPy
- Matplotlib

```bash
pip install numpy matplotlib
```

## Course Overview

This course teaches the fundamentals of computational chemistry and materials science through hands-on coding. You'll learn to represent, transform, and analyze atomic structures using pure Python and NumPy.

## Chapters

| # | Chapter | Topics |
|---|---------|--------|
| 1 | [Atoms in 3D Space](chapters/01_atoms_in_3d_space.ipynb) | Atom representation, coordinates, distances, angles, dihedrals |
| 2 | [Linear Algebra for Atomic Manipulation](chapters/02_linear_algebra_transformations.ipynb) | Rotation matrices, Rodrigues' formula, affine transformations |
| 3 | [Symmetry Operations and Point Groups](chapters/03_symmetry_operations.ipynb) | Symmetry operations, C₂ᵥ, C₃ᵥ, D₆ₕ, Tᵈ point groups |
| 4 | [Crystal Lattices and Unit Cells](chapters/04_crystal_lattices.ipynb) | 7 crystal systems, 14 Bravais lattices, fractional coordinates |
| 5 | [Building Crystal Structures](chapters/05_building_crystals.ipynb) | FCC, BCC, HCP, diamond, rocksalt, Wyckoff positions |
| 6 | [Miller Indices and Crystal Planes](chapters/06_miller_indices.ipynb) | Miller notation, d-spacing, zone axis, systematic absences |
| 7 | [Surface Creation and Slab Models](chapters/07_surface_slabs.ipynb) | Surface terminations, slab models, adsorbate placement |
| 8 | [Molecules - Building and Manipulating](chapters/08_molecules.ipynb) | Z-matrix, internal coordinates, conformations, RMSD alignment |
| 9 | [Advanced Transformations](chapters/09_advanced_transforms.ipynb) | Supercell matrices, strain tensors, cell reduction |
| 10 | [Exporting Structures](chapters/10_file_formats.ipynb) | XYZ, PDB, CIF, POSCAR, LAMMPS formats |

## Learning Objectives

By completing this course, you will be able to:

- **Represent atoms** in 3D Cartesian and fractional coordinates
- **Apply transformations** using rotation matrices and affine transforms
- **Understand symmetry** through point group operations
- **Build crystals** from lattice parameters and atomic bases
- **Work with Miller indices** to describe crystal planes and directions
- **Create surface slabs** with proper terminations for surface science
- **Manipulate molecules** including conformational changes
- **Transform unit cells** and generate supercells
- **Export structures** to standard file formats for simulations

## Mathematical Foundations

The course emphasizes mathematical understanding:

- **Vectors and matrices** for atomic positions and transformations
- **Rodrigues' rotation formula** for arbitrary axis rotations
- **Metric tensors** for non-orthogonal crystal systems
- **Reciprocal lattice** calculations
- **Strain tensors** for crystal deformations

## Key Classes Developed

Throughout the course, you'll build these core classes:

```python
Atom          # Single atom with element and position
Structure     # Collection of atoms
UnitCell      # Crystal lattice with fractional coordinates
Crystal       # Full crystal structure with lattice + basis
Slab          # Surface slab model with vacuum
Molecule      # Molecular structure with bonds
MillerIndex   # (hkl) plane notation
SymmetryOperation  # Rotation/reflection matrices
PointGroup    # Collection of symmetry operations
```

## Practice Exercises

Each chapter includes exercises to reinforce concepts:

- Build molecules from scratch
- Implement symmetry detection
- Calculate crystal properties
- Generate surface structures
- Convert between file formats

## Structure of Each Chapter

1. **Theory** - Mathematical background and conceptual understanding
2. **Implementation** - Python code with detailed comments
3. **Examples** - Worked examples with visualizations
4. **Exercises** - Practice problems to test understanding

## File Formats Covered

| Format | Use Case |
|--------|----------|
| XYZ | Simple coordinate files |
| PDB | Protein/biomolecule structures |
| CIF | Crystallographic databases |
| POSCAR | VASP calculations |
| LAMMPS | Molecular dynamics |

## Getting Started

1. Clone or download this repository
2. Install dependencies: `pip install numpy matplotlib`
3. Open Chapter 1 in Jupyter: `jupyter notebook chapters/01_atoms_in_3d_space.ipynb`
4. Work through chapters sequentially

## Tips for Success

- **Run all code cells** - don't just read, execute!
- **Modify examples** - try different parameters
- **Complete exercises** - solutions are in the exercise cells
- **Visualize often** - use the plotting functions provided

## License

Educational use. Feel free to modify and extend for your learning.
