# 🚀 lunasia-fpga-project-template

A clean, student-friendly template for managing **Vivado / Verilog** projects on GitHub.

## 🎯 Overview
This repository is organized for HDL development, simulation, and documentation.  
Use it to manage course projects, research experiments, or hardware prototypes.

## 📂 Folder Structure

```

src/           # HDL source files (Verilog/VHDL)
sim/           # Testbench and simulation files
constraints/   # FPGA board pin constraint files (.xdc)
scripts/       # Vivado or helper scripts
docs/          # Design documents and diagrams
data/          # Input/output data (ignored by git)

```

## 🧰 Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/<yourname>/<repo>.git
   cd <repo>
    ```

2. Open in Vivado:

   ```
   vivado -source scripts/create_project.tcl
   ```
   
3. Add your HDL files into `/src` and testbenches into `/sim`.

## 🧠 Notes

* Keep simulation/test data out of Git (`/data` is ignored by default).
* Commit logically:

  ```
  feat: add lidar timestamp module
  fix: correct UART frame alignment
  docs: update design flow in README
  ```

## 🧾 License

Licensed under the [MIT License](LICENSE).

## 👤 Author

**Your Name**
LushShepherd @ Neverland University
📧 [LushShepherd@users.noreply.github.com](mailto:LushShepherd@users.noreply.github.com)
