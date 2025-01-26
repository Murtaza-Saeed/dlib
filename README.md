# Dlib Compiled Binary Wheels for Python 3.7 - 3.12 on Windows (x64 CPUs)

This repository provides pre-compiled binary wheels (.whl files) for the Dlib library, making it easy to install on Python versions 3.7, 3.8, 3.9, 3.10, 3.11, and 3.12 on Windows (x64 architecture).

## Overview
If you have encountered issues such as "Failed to build dlib" or "Failed building wheel for dlib," this repository offers a straightforward solution. You can now install the Dlib and Face Recognition libraries without errors by following a few simple steps.

Watch the step-by-step installation tutorial here: **[Murtaza i Tech on YouTube](https://www.youtube.com/watch?v=cV4-uMobeM4)**.

### Topics Covered
- Fixing "Failed to build dlib" and "Failed building wheel for dlib" errors
- Resolving pip installation issues for Dlib and Face Recognition
- Installing Dlib and Face Recognition libraries on Python 3.7 - 3.12
- Troubleshooting installation problems related to CMake and legacy builds

## Installation Instructions
Follow these three steps to install Dlib and Face Recognition without errors:

### Step 1: Install CMake
Run the following command in your terminal or command prompt:
```bash
pip install cmake
```

### Step 2: Install Dlib
Download the appropriate `.whl` file for your Python version from this repository. Navigate to the folder where the file is located using the command prompt, and run:
```bash
pip install <filename>
```
Replace `<filename>` with the name of the downloaded `.whl` file.

#### Example Commands
- For Python 3.7:
  ```bash
  python -m pip install dlib-19.22.99-cp37-cp37m-win_amd64.whl
  ```
- For Python 3.8:
  ```bash
  python -m pip install dlib-19.22.99-cp38-cp38-win_amd64.whl
  ```
- For Python 3.9:
  ```bash
  python -m pip install dlib-19.22.99-cp39-cp39-win_amd64.whl
  ```
- For Python 3.10:
  ```bash
  python -m pip install dlib-19.22.99-cp310-cp310-win_amd64.whl
  ```
- For Python 3.11:
  ```bash
  python -m pip install dlib-19.24.1-cp311-cp311-win_amd64.whl
  ```
- For Python 3.12:
  ```bash
  python -m pip install dlib-19.24.99-cp312-cp312-win_amd64.whl
  ```

### Step 3: Install Face Recognition
Once Dlib is successfully installed, install the Face Recognition library using:
```bash
pip install face-recognition
```

### Notes
- The file name suffixes like `cp37` correspond to CPython version 3.7, `cp38` to CPython 3.8, and so on.
- Ensure that you are using the correct `.whl` file for your Python version and system architecture (Windows x64).

## Troubleshooting
If you encounter any issues, revisit the installation steps and ensure that:
- You have the correct version of Python installed.
- You downloaded the appropriate `.whl` file for your Python version.
- CMake is installed prior to installing Dlib.

## Support
For further assistance, please refer to the YouTube tutorial linked above or open an issue in this repository.

---

### Quick Links
- **[Dlib Official Documentation](http://dlib.net/)**
- **[Face Recognition GitHub Repository](https://github.com/ageitgey/face_recognition)**
