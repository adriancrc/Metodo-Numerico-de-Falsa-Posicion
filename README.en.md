# Closed Numerical Method: False Position (Regula Falsi)

🇪🇸 Versión en español disponible aquí: [README.md](README.md)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-Numerico-de-Falsa-Posicion)  
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/)

![GitHub Release](https://img.shields.io/github/v/release/adriancrc/Metodo-Numerico-de-Falsa-Posicion)
![Total Downloads](https://img.shields.io/github/downloads/adriancrc/Metodo-Numerico-de-Falsa-Posicion/total)
![Tested with MATLAB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fadriancrc%2FMetodo-Numerico-de-Falsa-Posicion%2Fmain%2Freport%2Fbadge%2Ftested_with.json)
![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![Use Case](https://img.shields.io/badge/Use-Educational-success)
![Author](https://img.shields.io/badge/Author-Adrián%20Quesada%20Martínez-blueviolet)
![Developed at ITCR](https://img.shields.io/badge/Developed%20at-ITCR-blue)

---

## 👨‍💻 Author
**Adrián José Quesada Martínez**  
*Tecnológico de Costa Rica (ITCR)*

---

## 📘 Description

This repository contains a MATLAB implementation of the **False Position Method** (also known as **Regula Falsi**), a closed numerical root-finding technique that improves convergence over the bisection method by using linear interpolation to approximate the root of a continuous function.

The algorithm is provided as an **interactive Live Script**, designed for educational use and ideal for numerical methods instruction.

---

## 🧠 Algorithm Summary

The **false position method** starts with an interval \([a, b]\) where \(f(a) \cdot f(b) < 0\) and estimates the root using the formula:

\[
x_r = b - \frac{f(b)(a - b)}{f(a) - f(b)}
\]

Each iteration performs the following steps:

1. Compute \(x_r\) using the formula above.
2. Evaluate \(f(x_r)\).
3. Update the interval based on the sign of \(f(x_r)\).
4. Repeat until the desired tolerance or maximum iterations is reached.

---

## ✨ Live Script Features

- **Editable inputs**: define the function, interval, tolerance, and maximum iterations.
- **Dynamic plots**: visualize the root approximation process.
- **Iteration table**: includes values for `a`, `b`, `xr`, `f(xr)`, and relative error.
- **Integrated documentation**: includes formulas, comments, and explanations.
- **Beginner-friendly design**: tailored for students and educators.

---

## 📚 Numerical Methods Concepts

- **Root-finding**: solving equations of the form \(f(x) = 0\).
- **Closed methods**: based on a sign change in the function.
- **Linear interpolation**: enhances root estimation over midpoint selection.
- **Error analysis**: relative error controls accuracy and convergence.

---

## 🚀 How to Use the Live Script

### 🔹 Option 1: Download

1. Download or clone this repository.
2. Open the `.mlx` file in MATLAB.

### 🔹 Option 2: [Open in MATLAB Online](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-Numerico-de-Falsa-Posicion)

- Log in using your MathWorks account.
- If you're a student or educator, use your institutional email to access the license.

---

## 💻 Required Product

- **MATLAB®**

---

## 📄 License

This project is licensed under the terms specified in the [`LICENSE`](LICENSE) file included in this repository.

---

## 📬 Support

Questions or suggestions?  
📧 [adquesada@itcr.ac.cr](mailto:adquesada@itcr.ac.cr)

---

© 2025 Adrián José Quesada Martínez
# Closed Numerical Method: False Position (Regula Falsi)

🇪🇸 Versión en español disponible aquí: [README.md](README.md)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-Numerico-de-Falsa-Posicion)  
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/)

![GitHub Release](https://img.shields.io/github/v/release/adriancrc/Metodo-Numerico-de-Falsa-Posicion)
![Total Downloads](https://img.shields.io/github/downloads/adriancrc/Metodo-Numerico-de-Falsa-Posicion/total)
![Tested with MATLAB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fadriancrc%2FMetodo-Numerico-de-Falsa-Posicion%2Fmain%2Freport%2Fbadge%2Ftested_with.json)
![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![Use Case](https://img.shields.io/badge/Use-Educational-success)
![Author](https://img.shields.io/badge/Author-Adrián%20Quesada%20Martínez-blueviolet)
![Developed at ITCR](https://img.shields.io/badge/Developed%20at-ITCR-blue)

---

## 👨‍💻 Author
**Adrián José Quesada Martínez**  
*Tecnológico de Costa Rica (ITCR)*

---

## 📘 Description

This repository contains a MATLAB implementation of the **False Position Method** (also known as **Regula Falsi**), a closed numerical root-finding technique that improves convergence over the bisection method by using linear interpolation to approximate the root of a continuous function.

The algorithm is provided as an **interactive Live Script**, designed for educational use and ideal for numerical methods instruction.

---

## 🧠 Algorithm Summary

The **false position method** starts with an interval \([a, b]\) where \(f(a) \cdot f(b) < 0\) and estimates the root using the formula:

\[
x_r = b - \frac{f(b)(a - b)}{f(a) - f(b)}
\]

Each iteration performs the following steps:

1. Compute \(x_r\) using the formula above.
2. Evaluate \(f(x_r)\).
3. Update the interval based on the sign of \(f(x_r)\).
4. Repeat until the desired tolerance or maximum iterations is reached.

---

## ✨ Live Script Features

- **Editable inputs**: define the function, interval, tolerance, and maximum iterations.
- **Dynamic plots**: visualize the root approximation process.
- **Iteration table**: includes values for `a`, `b`, `xr`, `f(xr)`, and relative error.
- **Integrated documentation**: includes formulas, comments, and explanations.
- **Beginner-friendly design**: tailored for students and educators.

---

## 📚 Numerical Methods Concepts

- **Root-finding**: solving equations of the form \(f(x) = 0\).
- **Closed methods**: based on a sign change in the function.
- **Linear interpolation**: enhances root estimation over midpoint selection.
- **Error analysis**: relative error controls accuracy and convergence.

---

## 🚀 How to Use the Live Script

### 🔹 Option 1: Download

1. Download or clone this repository.
2. Open the `.mlx` file in MATLAB.

### 🔹 Option 2: [Open in MATLAB Online](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-Numerico-de-Falsa-Posicion)

- Log in using your MathWorks account.
- If you're a student or educator, use your institutional email to access the license.

---

## 💻 Required Product

- **MATLAB®**

---

## 📄 License

This project is licensed under the terms specified in the [`LICENSE`](LICENSE) file included in this repository.

---

## 📬 Support

Questions or suggestions?  
📧 [adquesada@itcr.ac.cr](mailto:adquesada@itcr.ac.cr)

---

© 2025 Adrián José Quesada Martínez
