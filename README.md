# Single Port Memory (SPM) Design

## Project Overview
This repository contains the design and implementation of a Single Port Memory (SPM) module developed using the **OpenLane** VLSI flow. The SPM supports read and write operations for data storage.

## Features
- **Single Port Access**: Read/write via a single port.
- **8-Bit Data Width**: Handles 8-bit data.
- **OpenLane Integration**: Synthesized and laid out using OpenLane.
- **Configurable Address Space**: Adjustable memory depth.

## Directory Structure

my_spm/
├── src/                # Verilog/SystemVerilog source files
├── runs/               # OpenLane run outputs (excluded in .gitignore)
├── config.json         # OpenLane configuration (if applicable)
├── LICENSE             # License file
└── README.md           # This file


## Prerequisites
- **OpenLane**: Install via [OpenLane documentation](https://openlane.readthedocs.io/en/latest/).
- **Python 3.x**: For OpenLane scripts.
- **Git**: For repository management.

## Setup and Usage
1. **Clone the repository**:
   ```bash
   git clone git@github.com:sahanakulkarni-PD-VLSI/my_spm.git
   cd my_spm


2. Run OpenLane Flow:
Configure OpenLane environment.
Run:
bash
make run

3. Check runs/ for outputs (not tracked in Git).
Simulation:
Use testbenches in src/ with tools like Icarus Verilog.

Contributing
1.Fork the repository.
2.Create a branch (git checkout -b feature-branch).
3.Commit changes (git commit -m "Add feature").
4.Push (git push origin feature-branch).
5.Open a pull request.

License
MIT License

Contact
Email: sahanakulkarni0012@gmail.com

Designed by Sahana Kulkarni & Amit Airodagi for VLSI coursework.
