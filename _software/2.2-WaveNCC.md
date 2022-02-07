---
title: "WaveNCC"
excerpt: <b><span style="color:red;">Keywords</span></b> - <i>Python, quantum mechanics, numerical analysis</i>. <br/><br/>A program to compute the normalization coefficients of a given orthogonal 1-D complex wave function.<br/><img src='/images/WaveNCC.png' width="600">
collection: software
---

This program computes the normalization coefficients <img src="https://render.githubusercontent.com/render/math?math=\color{green}{c_n}"> of a given orthogonal 1-dimensional complex wave-function <img src="https://render.githubusercontent.com/render/math?math=\color{green}{\psi_n(x)}"> for a given *n* index, or for a whole set of orthogonal wave-functions. Additionally, it performs orthogonality and orthonormality checks and plots the normalized wave-functions shapes. More physical and mathematical information can be found [here](https://github.com/JustWhit3/WaveNCC/blob/main/doc/Background%20explanation.md).

The set of <img src="https://render.githubusercontent.com/render/math?math=\color{green}{\psi_n(x)}"> wave-functions is used in quantum mechanics to find a generic solution for the 1-D [Schrödinger equation](https://users.aber.ac.uk/ruw/teach/327/hatom.php) and in particular for the equation of the harmonic oscillator.

This program computes the coefficients only for a certain kind of wave-function, which should be:

- Orthogonal.
- Real or complex.
- 1-dimensional (therefore, with only one variable).
- Time independent.

The function may depends on an index *n* but this is not necessary, since the program can calculate the coefficients also if *n=0*.
> NB: equation color is green in order to improve the readability both for light and dark GitHub themes.

[Project link](https://github.com/JustWhit3/WaveNCC)
