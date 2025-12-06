# Research Journal

This repository contains my personal research and learning journal as I explore a wide range of mathematical and physical ideas. The goal isn’t perfection or polished work. I use it to document concepts I’m revisiting, topics I’m teaching myself ahead of time, and areas I’m curious about (like quantum information, Qiskit, and mathematical methods for physics).

Alongside my university studies, I’m also building technical depth in quantum systems, computational tools, and the mathematics needed for more advanced fields such as QFT. This journal is a central place to keep my notes, experiments, explanations, and any code that supports my learning.

---

## What’s in this repository?

The project contains LaTeX notes, image assets, and supporting files organised into folders.  
Below is a breakdown of what each folder contains and how it fits into the journal.

### ### `notes/`
This folder holds the LaTeX source for the main journal.

- `journal.main.tex` — the primary LaTeX file containing the actual content of the journal.  
  This is where most of the writing happens.

### ### `images/`
All image assets used in the journal.

These include:
- screenshots used in explanations (e.g. environment setup, row operations example)  
- may include annotated images to support the text in future

Whenever an image appears in the PDF, its file will be located here.

### ### `figures/`
Reserved for future polished figures, plots, or diagrams created externally.  
Currently contains only a placeholder but intended for:

- matplotlib/NumPy plots  
- TikZ-generated diagrams (if externalized)  
- high-quality figures used in later sections
- other figures obtained from external sources

### ### `code/`
A workspace for any programming related to the journal.

This may include:
- Python scripts  
- NumPy experiments  
- Qiskit programs  
- Jupyter notebook exports  

As my research interests evolve (quantum systems, simulations, high-energy particle physics, etc.), this folder will house the computational side of the project.

### ### `misc/`
Supporting files that don’t fit into the main flow of the notes.

- `references.bib` — bibliography for the journal via biblatex  
- `latexmkrc.tex` — project-specific compiler settings (e.g. enabling `-shell-escape` for minted/Jupyter code blocks)

### `README.md`
This document — an overview of the project, structure, and purpose.

---

## 📄 Project Purpose

This journal acts as a centre for my research interests and development, outside where I may currently be in my degree course. 
Its goals include:

- consolidating core mathematical prerequisites  
- building a structured understanding of quantum information  
- learning how to use tools like Qiskit in practice  
- preparing for deeper study (operators, Hilbert spaces, QFT, etc.)  
- creating a reference I can return to throughout my degree and beyond  
- practicing clean documentation and version control with GitHub + Overleaf  

---

## Build & Compile Notes

This project is built with **LaTeX** and designed to compile using Overleaf or a local TeX installation.

- Requires `-shell-escape` enabled for Jupyter/minted code blocks  
- Uses `biblatex` with a `.bib` file located in `misc/references.bib`  
- Images are loaded from `images/`  
- Figures may later use `figures/` 

If compiling locally, ensure you have:
- `pdflatex` or `xelatex`  
- `minted` (Python Pygments installed)  
- the fonts and packages Overleaf includes by default  

---

## 🧩 Future Plans

- Add code demonstrations using Qiskit  
- Move heavy sections into structured chapter files in `notes/` as the journal grows  
- Add plots and visualisations generated from Python  
- Start a module-style breakdown for linear algebra, vector calculus, and operators  
- Eventually create a second repository for more advanced research work

---

If you'd like to explore the content, feel free to browse the `notes/` or open the PDF once compiled. Naturally, this journal will evolve over time as I progress through my degree and independent studies.
