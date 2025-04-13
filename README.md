# Master's Thesis – 2025

This repository contains all related files and artifacts for my Master's thesis titled:

**"Deployment and Testing of an Enterprise-Facing Private 5G Solution (Aether) in a VM-Based Environment"**

The thesis explores how Aether, an open-source platform developed by the Open Networking Foundation (ONF), can be deployed and tested in resource-constrained environments using multiple blueprints. It includes stress testing, log analysis, performance metrics, and detailed system architecture for enterprise-facing private 5G networks.

---

## Repository Structure

```
Thesis-2025/
├── Demo/
│   └── Video demonstrating UPF testing using runtime operation control (ROC) of the deployed Private 5G network on a virtual machine (VM).
│
├── Deployment Diagrams/
│   └── Diagrams representing the network architecture, blueprint composition, and deployment layouts of Aether in VM setups.
│
├── Logs&CallFlows Analysis/
│   ├── GNBSIM log files captured during UE stress tests
│   ├── Visualized call flows (registration, PDU sessions, etc.)
│   └── Latency analysis and metrics plotted using Python scripts
│
├── ThesisLatex/
│   ├── main.tex                 # Main LaTeX file for compiling the complete thesis
│   ├── chapters/                # Chapter-wise LaTeX files (Introduction, Methodology, Results, etc.)
│   ├── appendices/              # Supplementary materials and data
│   ├── images/                  # All figures, diagrams, and illustrations used in the thesis
│   └── references/              # Bibliography and citation files (e.g., references.bib)
│
├── Thesis.pdf                  # Final compiled PDF version of the thesis
├── LICENSE                     # License for use and distribution (MIT)
└── README.md                   # You're reading it now :)
```

---

## View the Final Thesis (PDF)

You can download or read the final compiled version of the thesis here:

[**Thesis.pdf**](./Thesis.pdf)


## How to Compile the Thesis (LaTeX)

You can compile the LaTeX thesis either on your local machine or using Overleaf.

### Local Compilation (Command Line)

Make sure you have a LaTeX distribution installed (such as **TeX Live** or **MiKTeX**). Then run:

```bash
cd ThesisLatex

pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

This will generate `main.pdf` with all figures, citations, and references.

>  Alternatively, upload the `ThesisLatex` folder to Overleaf and compile online.

---

##  License

This project is licensed under the [MIT License](LICENSE).  
Feel free to reuse the LaTeX structure or figures with attribution.

---

## Author

**Hassan Shabir**  
MSc in Computer Science and Networking  
University of Pisa – 2025  
**Thesis Advisors**: Prof: Rosario G. Garroppo and Prof: Alessio Giorgetti

---
