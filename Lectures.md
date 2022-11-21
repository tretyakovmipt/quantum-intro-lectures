# Lecture 1

### Two-level system

$$
|\psi\rangle = a|1\rangle+be^{-i\phi}\ |2\rangle
$$

$$
a^2+b^2=1
$$

$$
|1\rangle\langle1|+|2\rangle\langle2|\approx\hat{I}
$$

### Basics

$|\psi\rangle -$ “*ket-vector*” aka *quantum state* aka *wavefunction* is a vector in Hilbert space. For us, it’s a column with complex numbers.

$\langle\psi|=(|\psi\rangle)^{\dag} -$ “*bra-vector*”  is a linear form. For us, it’s a row with complex numbers obtained from $|\psi\rangle$ by transposing and complex conjugation.

$\langle\psi|\phi\rangle$ - *scalar product* aka *inner product* aka *dot-product* is a complex number.

 $|\phi\rangle\langle\psi|=|\phi\rangle\otimes\langle\psi|$- *tensor product*. It acts as a linear operator and is typically written as a matrix.

### True 2-level system: electron spin

$$
\hat{H} = -\hat{\mathbf{\mu}}\cdot\mathbf{B}=-\gamma\left(\hat{s}_xB_x+\hat{s}_yB_y+\hat{s}_zB_z\right)
$$

$$
\gamma = -2\dfrac{\mu_B}{\hbar}
$$

$$
\hat{s}_i=\dfrac{\hbar}{2}\hat{\sigma}_i
$$

$$
\hat{H}=\dfrac{1}{2}\mu_B\left(\hat{\sigma}_xB_x+\hat{\sigma}_yB_y+\hat{\sigma}_zB_z\right)=\dfrac{\mu_B}{2}\hat{\mathbf{\sigma}}\cdot\mathbf{B}
$$

Pauli matrices in z-basis (eigenvectors of $\hat{\sigma}_z$):
