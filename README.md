# Método Numérico Cerrado de Falsa Posición

🌐 This README is also available in English 🇺🇸: [README.en.md](README.en.md)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-Numerico-de-Falsa-Posicion)  
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/)

![GitHub Release](https://img.shields.io/github/v/release/adriancrc/Metodo-Numerico-de-Falsa-Posicion)
![Total Downloads](https://img.shields.io/github/downloads/adriancrc/Metodo-Numerico-de-Falsa-Posicion/total)
![Tested with MATLAB](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/adriancrc/Metodo-Numerico-de-Falsa-Posicion/main/report/badge/tested_with.json)
![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![Use Case](https://img.shields.io/badge/Use-Educational-success)
![Author](https://img.shields.io/badge/Author-Adrián%20Quesada%20Martínez-blueviolet)
![Developed at ITCR](https://img.shields.io/badge/Developed%20at-ITCR-blue)

---

## 👨‍💻 Autor
**Adrián José Quesada Martínez**  
*Instituto Tecnológico de Costa Rica*

---

## 📘 Descripción

Este repositorio contiene una implementación en MATLAB del **método numérico de falsa posición** (también conocido como **regla falsa**), el cual mejora la convergencia con respecto al método de bisección al usar interpolación lineal para estimar la raíz de una función continua.

Desarrollado como un **Live Script interactivo**, este recurso está enfocado en la docencia de métodos numéricos, facilitando la comprensión visual del procedimiento iterativo.

---

## 🧠 Resumen del algoritmo

El **método de falsa posición** parte de un intervalo \([a, b]\) donde \(f(a) \cdot f(b) < 0\), y estima la raíz mediante la fórmula:

\[
x_r = b - \frac{f(b)(a - b)}{f(a) - f(b)}
\]

En cada iteración:

1. Se calcula \(x_r\) con la fórmula anterior.
2. Se evalúa \(f(x_r)\).
3. Se actualiza el intervalo manteniendo el cambio de signo.
4. Se repite hasta alcanzar la tolerancia deseada o el número máximo de iteraciones.

---

## ✨ Características del Live Script

- **Interfaz clara y editable**: permite definir la función, el intervalo, la tolerancia y el número de iteraciones.
- **Gráficas dinámicas**: visualiza la evolución de la raíz aproximada.
- **Tablas organizadas**: muestra las iteraciones con valores clave y errores relativos.
- **Comentarios explicativos**: ideales para estudiantes y docentes.
- **Diseño intuitivo**: pensado para facilitar el aprendizaje.

---

## 📚 Fundamentos de métodos numéricos

- **Raíces de ecuaciones no lineales**: se busca \(f(x) = 0\).
- **Métodos cerrados**: aprovechan un intervalo con cambio de signo.
- **Interpolación lineal**: técnica que acelera la estimación de raíces.
- **Errores relativos**: control del proceso iterativo.

---

## 🚀 Cómo usar el script interactivo

### 🔹 Opción 1: Descargar

1. Descargue o clone este repositorio.
2. Abra el archivo `.mlx` en MATLAB.

### 🔹 Opción 2: [Abrir en MATLAB Online](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-Numerico-de-Falsa-Posicion)

- Inicie sesión con su cuenta MathWorks.
- Puede usar su correo institucional si es estudiante/docente.

---

## 💻 Producto requerido

- **MATLAB®**

---

## 📄 Licencia

Este proyecto está licenciado bajo los términos definidos en el archivo [`LICENSE`](LICENSE) incluido en este repositorio.

---

## 📬 Soporte

¿Consultas o sugerencias?  
📧 [adquesada@itcr.ac.cr](mailto:adquesada@itcr.ac.cr)

---

## ⭐ ¡No olvides calificar!

Si este material te fue útil, apóyame dejando una calificación positiva ⭐⭐⭐⭐⭐ en la página del proyecto.  
¡Tu retroalimentación ayuda a mejorar y seguir compartiendo recursos!

[![Califica este proyecto](https://img.shields.io/badge/★★★★★-Califica%20en%20File%20Exchange-blueviolet?style=for-the-badge)](https://la.mathworks.com/matlabcentral/fileexchange/181740-metodo-numerico-de-falsa-posicion)

---


© 2025 Adrián José Quesada Martínez
