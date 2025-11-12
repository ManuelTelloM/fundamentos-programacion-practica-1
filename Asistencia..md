

# Tecnológico de Software

## Materia: Fundamentos de Álgebra

### Alumno: Manuel Jesus Tello May

### Grupo: 1B.

### Actividad #16 - Matrices

### Profesor: Jorge Pedrozo.
---

## 1. Identificación de matrices


$$
A = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}, 
$$
#### Matriz Identidad 
Es una matriz identidad debido a que los valores dentro de la matriz son iguales.

---
$$
B = \begin{pmatrix} 3 & 0 & 0 \\ 0 & -2 & 0 \\ 0 & 0 & 5 \end{pmatrix}, 
$$

#### Matriz Diagonal  
Es una matriz diagonal porque todos los elementos fuera de la diagonal son cero.

---
$$
C = \begin{pmatrix} 2 & 1 & 4 \\ 1 & 3 & 5 \\ 4 & 5 & 6 \end{pmatrix}, 
$$


#### Matriz Simétrica.  
Es una matriz simétrica porque los valores respecto a la diagonal principal son iguales.

---

$$
D = \begin{pmatrix} 1 & 2 & 3 \\ 0 & 4 & 5 \\ 0 & 0 & 6 \end{pmatrix}
$$
#### Matriz triangular superior. 
Es una matriz triangular superior porque los elementos debajo de la diagonal principal son cero.



---
### Ejercicio 2: Operaciones básicas  

Dadas las matrices:

$$
A = \begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}, \qquad
B = \begin{pmatrix} 5 & 2 \\ -1 & 3 \end{pmatrix}
$$

Calcula:  

####  $A + B$

$$
A + B = \begin{pmatrix} 2+5 & -1+2 \\ 3+(-1) & 4+3 \end{pmatrix}
       = \begin{pmatrix} 7 & 1 \\ 2 & 7 \end{pmatrix}
$$

---

####   $2A - B$

$$ 2A - B = 2 \begin{bmatrix}
2 & -1 \\
3 & 4
\end{bmatrix} - \begin{bmatrix}
5 & 2 \\
-1 & 3
\end{bmatrix} = \begin{bmatrix}
4 & -2 \\
6 & 8
\end{bmatrix} - \begin{bmatrix}
5 & 2 \\
-1 & 3
\end{bmatrix} = \begin{bmatrix}
-1 & -4 \\
7 & 5
\end{bmatrix} $$

---

####   $AB$

$$
AB = \begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}
     \begin{pmatrix} 5 & 2 \\ -1 & 3 \end{pmatrix}
   = \begin{pmatrix}
   (2)(5)+(-1)(-1) & (2)(2)+(-1)(3) \\
   (3)(5)+(4)(-1) & (3)(2)+(4)(3)
   \end{pmatrix}
   = \begin{pmatrix} 11 & 1 \\ 11 & 18 \end{pmatrix}
$$

---

####  $BA$

$$
BA = \begin{pmatrix} 5 & 2 \\ -1 & 3 \end{pmatrix}
     \begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}
   = \begin{pmatrix}
   (5)(2)+(2)(3) & (5)(-1)+(2)(4) \\
   (-1)(2)+(3)(3) & (-1)(-1)+(3)(4)
   \end{pmatrix}
   = \begin{pmatrix} 16 & 3 \\ 7 & 13 \end{pmatrix}
$$

---

####  Transpuesta de $A$

$$
A^T = \begin{pmatrix} 2 & -1 \\ 3 & 4 \end{pmatrix}^T
    = \begin{pmatrix} 2 & 3 \\ -1 & 4 \end{pmatrix}
$$

---
### Ejercicio 3: Multiplicación de tres matrices. 

$$
A = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}, \qquad
B = \begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix}, \qquad
C = \begin{pmatrix} 1 & 1 \\ 0 & 2 \end{pmatrix}
$$

Verifica que (AB)C = A(BC)

---

 **Calcular AB**

$$
AB = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
     \begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix}
   = \begin{pmatrix}
   (1)(2)+(2)(1) & (1)(0)+(2)(3) \\
   (3)(2)+(4)(1) & (3)(0)+(4)(3)
   \end{pmatrix}
   = \begin{pmatrix} 4 & 6 \\ 10 & 12 \end{pmatrix}
$$

---

**Calcular (AB)C**

$$
(AB)C = \begin{pmatrix} 4 & 6 \\ 10 & 12 \end{pmatrix}
         \begin{pmatrix} 1 & 1 \\ 0 & 2 \end{pmatrix}
       = \begin{pmatrix}
       (4)(1)+(6)(0) & (4)(1)+(6)(2) \\
       (10)(1)+(12)(0) & (10)(1)+(12)(2)
       \end{pmatrix}
       = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
$$

---

**Calcular BC**

$$
BC = \begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix}
      \begin{pmatrix} 1 & 1 \\ 0 & 2 \end{pmatrix}
    = \begin{pmatrix}
    (2)(1)+(0)(0) & (2)(1)+(0)(2) \\
    (1)(1)+(3)(0) & (1)(1)+(3)(2)
    \end{pmatrix}
    = \begin{pmatrix} 2 & 2 \\ 1 & 7 \end{pmatrix}
$$

---

**Calcular A(BC)**

$$
A(BC) = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
         \begin{pmatrix} 2 & 2 \\ 1 & 7 \end{pmatrix}
       = \begin{pmatrix}
       (1)(2)+(2)(1) & (1)(2)+(2)(7) \\
       (3)(2)+(4)(1) & (3)(2)+(4)(7)
       \end{pmatrix}
       = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
$$

---

#### Comprobando.

$$
(AB)C = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}, \qquad
A(BC) = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
$$

Si son iguales, entonces:

$$
(AB)C = A(BC)
$$

---




