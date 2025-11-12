
# # Tecnológico de Software

## Materia: Fundamentos de Álgebra  
**Alumno:** Manuel Jesús Tello May  
**Grupo:** 1B  
**Actividad #16:** Matrices  
**Profesor:** Jorge Pedrozo  

---

## 1. Identificación de Matrices

### Matriz Identidad

$$
A = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}
$$

**Descripción:**  
Es una matriz identidad, ya que todos los elementos de la diagonal principal son 1 y los demás son 0.

---

### Matriz Diagonal

$$
B = \begin{pmatrix} 3 & 0 & 0 \\ 0 & -2 & 0 \\ 0 & 0 & 5 \end{pmatrix}
$$

**Descripción:**  
Es una matriz diagonal porque todos los elementos fuera de la diagonal principal son cero.

---

### Matriz Simétrica

$$
C = \begin{pmatrix} 2 & 1 & 4 \\ 1 & 3 & 5 \\ 4 & 5 & 6 \end{pmatrix}
$$

**Descripción:**  
Es una matriz simétrica, ya que los valores respecto a la diagonal principal son iguales.

---

### Matriz Triangular Superior

$$
D = \begin{pmatrix} 1 & 2 & 3 \\ 0 & 4 & 5 \\ 0 & 0 & 6 \end{pmatrix}
$$

**Descripción:**  
Es una matriz triangular superior porque los elementos debajo de la diagonal principal son cero.

---

## 2. Operaciones Básicas

Dadas las matrices:

$$
A = \begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}, \quad
B = \begin{pmatrix} 5 & 2 \\ -1 & 3 \end{pmatrix}
$$

---

### a) Suma de Matrices

$$
A + B =
\begin{pmatrix} 2+5 & -1+2 \\ 3+(-1) & 4+3 \end{pmatrix}
= \begin{pmatrix} 7 & 1 \\ 2 & 7 \end{pmatrix}
$$

---

### b) Operación \( 2A - B \)

$$
2A - B =
2\begin{pmatrix}
2 & -1 \\ 3 & 4
\end{pmatrix}
-
\begin{pmatrix}
5 & 2 \\ -1 & 3
\end{pmatrix}
=
\begin{pmatrix}
4 & -2 \\ 6 & 8
\end{pmatrix}
-
\begin{pmatrix}
5 & 2 \\ -1 & 3
\end{pmatrix}
=
\begin{pmatrix}
-1 & -4 \\ 7 & 5
\end{pmatrix}
$$

---

### c) Producto \( AB \)

$$
AB =
\begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}
\begin{pmatrix} 5 & 2 \\ -1 & 3 \end{pmatrix}
=
\begin{pmatrix}
(2)(5)+(-1)(-1) & (2)(2)+(-1)(3) \\
(3)(5)+(4)(-1) & (3)(2)+(4)(3)
\end{pmatrix}
=
\begin{pmatrix} 11 & 1 \\ 11 & 18 \end{pmatrix}
$$

---

### d) Producto \( BA \)

$$
BA =
\begin{pmatrix} 5 & 2 \\ -1 & 3 \end{pmatrix}
\begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}
=
\begin{pmatrix}
(5)(2)+(2)(3) & (5)(-1)+(2)(4) \\
(-1)(2)+(3)(3) & (-1)(-1)+(3)(4)
\end{pmatrix}
=
\begin{pmatrix} 16 & 3 \\ 7 & 13 \end{pmatrix}
$$

---

### e) Transpuesta de \( A \)

$$
A^T =
\begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}^T
=
\begin{pmatrix} 2 & 3 \\ -1 & 4 \end{pmatrix}
$$

---

## 3. Multiplicación de Tres Matrices

Sean las matrices:

$$
A = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}, \quad
B = \begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix}, \quad
C = \begin{pmatrix} 1 & 1 \\ 0 & 2 \end{pmatrix}
$$

Comprobemos que:

$$
(AB)C = A(BC)
$$

---

### Paso 1: Calcular \( AB \)

$$
AB =
\begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
\begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix}
=
\begin{pmatrix}
(1)(2)+(2)(1) & (1)(0)+(2)(3) \\
(3)(2)+(4)(1) & (3)(0)+(4)(3)
\end{pmatrix}
=
\begin{pmatrix} 4 & 6 \\ 10 & 12 \end{pmatrix}
$$

---

### Paso 2: Calcular \( (AB)C \)

$$
(AB)C =
\begin{pmatrix} 4 & 6 \\ 10 & 12 \end{pmatrix}
\begin{pmatrix} 1 & 1 \\ 0 & 2 \end{pmatrix}
=
\begin{pmatrix}
(4)(1)+(6)(0) & (4)(1)+(6)(2) \\
(10)(1)+(12)(0) & (10)(1)+(12)(2)
\end{pmatrix}
=
\begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
$$

---

### Paso 3: Calcular \( BC \)

$$
BC =
\begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix}
\begin{pmatrix} 1 & 1 \\ 0 & 2 \end{pmatrix}
=
\begin{pmatrix}
(2)(1)+(0)(0) & (2)(1)+(0)(2) \\
(1)(1)+(3)(0) & (1)(1)+(3)(2)
\end{pmatrix}
=
\begin{pmatrix} 2 & 2 \\ 1 & 7 \end{pmatrix}
$$

---

### Paso 4: Calcular \( A(BC) \)

$$
A(BC) =
\begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
\begin{pmatrix} 2 & 2 \\ 1 & 7 \end{pmatrix}
=
\begin{pmatrix}
(1)(2)+(2)(1) & (1)(2)+(2)(7) \\
(3)(2)+(4)(1) & (3)(2)+(4)(7)
\end{pmatrix}
=
\begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
$$

---

### Paso 5: Comprobación

$$
(AB)C = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}, \quad
A(BC) = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
$$

**Conclusión:**  
Ambas matrices son iguales, por lo tanto:

$$
(AB)C = A(BC)
$$

Se cumple la propiedad asociativa de la multiplicación de matrices.

---





























