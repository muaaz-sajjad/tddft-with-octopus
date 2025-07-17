# TDDFT with Octopus 🐙

This repository provides a minimalist and practical guide to performing real-time Time-Dependent Density Functional Theory (TDDFT) simulations using [Octopus](https://www.octopus-code.org). It includes clean input files, selected outputs, and tools to visualize optical spectra using both **Gnuplot** and **Python**.

## 🎯 Purpose

To serve as a hands-on collection of Octopus TDDFT simulations focused on optical spectra, built from official tutorials and extended projects.

## 📁 Structure

tddft-with-octopus/
│
├── methane-optical-spectra/     # TDDFT of methane molecule  
│   ├── inp/                     # Input files for Octopus  
│   ├── out/                     # Selected output files  
│   ├── plots/                   # Generated plots  
│   ├── README.md                # Notes for this calculation  
│
├── tutorials/                   # Notes on Octopus tutorials  
│   └── tutorial_list.md  
│
├── utils/                       # Plotting scripts  
│   ├── plot_spectrum.py        # Python script  
│   └── plot_spectrum.gnu       # Gnuplot script  
│
├── .gitignore  
├── LICENSE  
└── README.md  

## 🔧 Requirements

- **Octopus** 12.1 or later  
- **Python 3.x** with:
  - `numpy`
  - `matplotlib`
- **Gnuplot** (for `.gnu` scripts)

## 📊 Visualization

### Using Python

Run the Python script:

    python utils/plot_spectrum.py

### Using Gnuplot

Run the Gnuplot script:

    gnuplot utils/plot_spectrum.gnu

Both scripts visualize the absorption spectrum using the file:

    out/td.general/optical_spectrum.dat

## ✅ Completed Projects

- [x] Optical spectra of Methane  
  [Tutorial](https://www.octopus-code.org/documentation/16/tutorial/response/optical_spectra_from_time-propagation/)

## 🚀 Getting Started

Clone the repo:

    git clone https://github.com/<your-username>/tddft-with-octopus.git
    cd tddft-with-octopus

## 📝 License

MIT License
