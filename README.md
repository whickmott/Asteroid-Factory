# Asteroid Factory

This repository hosts the compiled binary releases for **Asteroid Factory**, a cross-platform tool for procedural asteroid generation and geophysical simulation.

> **Note:** This repository contains executable releases only. No source code is hosted here.

## 📚 Citation

If you use Asteroid Factory in your research, please cite it as:
```bibtex
@software{Hickmott_Asteroid_Factory_-_2025,
author = {Hickmott, William and Hoettges, Kai},
doi = {10.5281/zenodo.17957777},
license = {MIT},
month = dec,
title = {{Asteroid Factory - A cross-platform tool for procedural asteroid generation and geophysical simulation}},
url = {https://github.com/whickmott/Asteroid_Factory},
version = {1.2-pre-release},
year = {2025}
}
```

## 📦 Downloads

Please download the appropriate version for your operating system from the **[Releases](../../releases)** page.

| Platform | Architecture | File Description |
| :--- | :--- | :--- |
| **Windows** | x64 | Standalone executable (`.exe`) |
| **macOS** | Apple Silicon (M1/M2/M3) | Native ARM64 binary |
| **macOS** | Intel | x64 binary for older Macs |
| **Linux** | x64 | Generic Linux binary |

---

## 🚀 Installation & Running

Since these applications are distributed as standalone binaries without an installer, you may need to set execution permissions on macOS and Linux.

### 🪟 Windows
1.  Download the **Windows (x64)** zip file.
2.  Right-click the zip and select **Extract All**.
3.  Open the folder and double-click `Asteroid Factory.exe` to launch.

### 🍎 macOS
**Important:** As this software is not notarised by the Apple App Store, you must manually allow it to run.

1.  Download the zip file matching your processor (Apple Silicon or Intel).
2.  Unzip the folder.
3.  **Fix Permissions:**
    * Open the **Terminal** app.
    * Type `chmod +x ` (include the space at the end).
    * Drag the file named `Asteroid Factory` (it has no extension) from the Finder window into the Terminal.
    * Press **Enter**.
4.  **First Run (Gatekeeper):**
    * Right-click (or Control-click) the `Asteroid Factory` file in Finder.
    * Select **Open** from the context menu.
    * Click **Open** in the warning dialogue box.

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
