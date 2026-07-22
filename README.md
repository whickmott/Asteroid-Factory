# Asteroid Factory

This repository hosts the compiled binary releases for **Asteroid Factory**, a cross-platform tool for procedural asteroid generation and geophysical simulation.

> **Note:** This repository contains executable releases only. No source code is hosted here.

## 📚 Citation

If you use Asteroid Factory in your research, please cite it as:
```bibtex
@software{Hickmott_Asteroid_Factory_-_2025,
author = {Hickmott, William and Zhou, Jiafeng and Soldini, Stefania and Hoettges, Kai},
doi = {10.5281/zenodo.17957777},
license = {MIT},
title = {{Asteroid Factory - A cross-platform tool for procedural asteroid generation and geophysical simulation}},
url = {https://github.com/whickmott/Asteroid_Factory},
version = {v1.0.0},
year = {2026}
}
```

## 📦 Downloads

Please download the appropriate version for your operating system from the **[Releases](../../releases)** page.

| Platform | Architecture | File Description |
| :--- | :--- | :--- |
| **Windows** | x64 | Standalone executable (`.exe`) |
| **Linux** | x64 | Generic Linux binary |

---

## 🚀 Installation & Running

Since these applications are distributed as standalone binaries without an installer, you may need to set execution permissions on macOS and Linux.

### 🪟 Windows
1.  Download the **Windows (x64)** zip file.
2.  Right-click the zip and select **Extract All**.
3.  Open the folder and double-click `Asteroid Factory.exe` to launch.

### 🐧 Linux
1.  Download the **Linux (x64)** zip file.
2.  Extract the contents.
3.  Open a terminal in the extracted folder.
4.  Make the file executable:
    ```bash
    chmod +x Asteroid Factory
    ```
5.  Run the application:
    ```bash
    ./Asteroid Factory
    ```

---

## ✨ Key Features

* **Procedural Generation:** Create voxelised asteroid models from STL files using multi-scale Gaussian Random Fields.
* **Physics Simulation:** Automatically calculates Density, Permittivity, Thermal Conductivity, and Seismic Velocities.
* **HDF5 Export:** Saves all generated fields into a hierarchical HDF5 format for scientific analysis.
* **Visualisation:** Includes a built-in HDF5 slice viewer and a lightweight 3D wireframe previewer.

---

## 📝 Licence

[MIT Licence](LICENSE)
