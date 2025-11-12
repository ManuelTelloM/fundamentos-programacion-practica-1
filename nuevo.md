
# Tecnológico de Software
 
## Materia: Fundamentos de Álgebra

### Alumno: Manuel Jesús Tello May

### Grupo: 1B

### Actividad #16 - Matrices

### Profesor: Jorge Pedrozo

  ---

## 1. Identificación de matrices

  ### Matriz Identidad

$$
A = \begin{pmatrix}  
1 & 0 \\
0 & 1  \end{pmatrix}
$$

  Es una matriz identidad debido a que los valores dentro de la matriz son iguales.

 ---

### Matriz Diagonal

 $$
B = \begin{pmatrix}  
   3 & 0 & 0 \\
   0 & -2 & 0 \\
   0 & 0 & 5  \end{pmatrix}
$$

  Es una matriz diagonal porque todos los elementos fuera de la diagonal son cero.

 ---

### Matriz Simétrica

$$
C = \begin{pmatrix}  
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6  \end{pmatrix}
$$

Es una matriz simétrica porque los valores respecto a la diagonal principal son iguales.

  ---

### Matriz Triangular Superior

$$
D = \begin{pmatrix}  1 & 2 & 3 \\
 0 & 4 & 5 \\
 0 & 0 & 6  \end{pmatrix}
$$

Es una matriz triangular superior porque los elementos debajo de la diagonal principal son cero.

  

---
  
## 2. Operaciones básicas

  Dadas las matrices:

$$
A = \begin{pmatrix}  
2 & -1 \\
3 & 4  \end{pmatrix}, \quad
B = \begin{pmatrix}
 5 & 2 \\
 -1 & 3  \end{pmatrix}
$$

  ---

###  Suma de matrices A + B

$$
A + B = \begin{pmatrix}  
2+5 & -1+2 \\
3+(-1) & 4+3  \end{pmatrix}
= \begin{pmatrix}  
7 & 1 \\
2 & 7  \end{pmatrix}
$$

  ---

###  Operación 2A - B

$$  
2A - B = 2  \begin{bmatrix}
2 & -1  \\
3 & 4
\end{bmatrix}  -  \begin{bmatrix}
5 & 2  \\
-1 & 3
\end{bmatrix} = \begin{bmatrix}
4 & -2  \\
6 & 8
\end{bmatrix}  -  \begin{bmatrix}
5 & 2  \\
-1 & 3
\end{bmatrix} = \begin{bmatrix}
-1 & -4  \\
7 & 5
\end{bmatrix}  
$$

---


### Producto AB

$$
AB = \begin{pmatrix}  
2 & -1 \\
3 & 4  \end{pmatrix}
\begin{pmatrix}  
5 & 2 \\
-1 & 3  \end{pmatrix}
= \begin{pmatrix}
(2)(5)+(-1)(-1) & (2)(2)+(-1)(3)  \\
(3)(5)+(4)(-1) & (3)(2)+(4)(3)
\end{pmatrix}
= \begin{pmatrix}  
11 & 1 \\ 
11 & 18  \end{pmatrix}
$$

  ---

### Producto BA

  $$ 
  BA = \begin{bmatrix}
5 & 2  \\
-1 & 3
\end{bmatrix}  \begin{bmatrix}
2 & -1  \\
3 & 4
\end{bmatrix} = \begin{bmatrix}
(5\cdot2)  +  (2\cdot3) & (5\cdot-1)  +  (2\cdot4)  \\
(-1\cdot2)  +  (3\cdot3) & (-1\cdot-1)  +  (3\cdot4)
\end{bmatrix} = \begin{bmatrix}
16 & 3  \\
7 & 13
\end{bmatrix}  
$$

 ---

###  Transpuesta de A

  $$
A^T = \begin{pmatrix}  
2 & -1 \\
3 & 4  \end{pmatrix}^T
= \begin{pmatrix}
 2 & 3 \\
 -1 & 4  \end{pmatrix}
$$

---

## 3. Multiplicación de tres matrices

Sean:

$$
A = \begin{pmatrix}  
1 & 2 \\ 
3 & 4  \end{pmatrix}, \quad
B = \begin{pmatrix} 
2 & 0 \\
1 & 3  \end{pmatrix}, \quad
C = \begin{pmatrix} 
1 & 1 \\
0 & 2  \end{pmatrix}
$$

  **Comprobemos que (AB)C = A(BC)**

  **Calcular AB**

  $$
AB = \begin{pmatrix}  
1 & 2 \\
3 & 4  \end{pmatrix}
\begin{pmatrix} 
2 & 0 \\
1 & 3  \end{pmatrix}
= \begin{pmatrix}
(1)(2)+(2)(1) & (1)(0)+(2)(3)  \\
(3)(2)+(4)(1) & (3)(0)+(4)(3)
\end{pmatrix}
= \begin{pmatrix} 
4 & 6 \\
10 & 12  \end{pmatrix}
$$

  ---

**Calcular (AB)C**

$$
(AB)C = \begin{pmatrix} 
4 & 6 \\
10 & 12  \end{pmatrix}
\begin{pmatrix} 
1 & 1 \\
0 & 2  \end{pmatrix}
= \begin{pmatrix}
(4)(1)+(6)(0) & (4)(1)+(6)(2)  \\
(10)(1)+(12)(0) & (10)(1)+(12)(2)
\end{pmatrix}
= \begin{pmatrix} 
4 & 16 \\
10 & 34  \end{pmatrix}
$$

  
---

**Calcular BC**

 $$
BC = \begin{pmatrix} 
2 & 0 \\
1 & 3  \end{pmatrix}
\begin{pmatrix} 
1 & 1 \\
0 & 2  \end{pmatrix}
= \begin{pmatrix}
(2)(1)+(0)(0) & (2)(1)+(0)(2)  \\
(1)(1)+(3)(0) & (1)(1)+(3)(2)
\end{pmatrix}
= \begin{pmatrix} 
2 & 2 \\
1 & 7  \end{pmatrix}
$$

  ---

**Calcular A(BC)**

  $$
A(BC) = \begin{pmatrix} 
1 & 2 \\
3 & 4  \end{pmatrix}
\begin{pmatrix} 
2 & 2 \\
1 & 7  \end{pmatrix}
= \begin{pmatrix}
(1)(2)+(2)(1) & (1)(2)+(2)(7)  \\
(3)(2)+(4)(1) & (3)(2)+(4)(7)
\end{pmatrix}
= \begin{pmatrix}  
4 & 16 \\
10 & 34  \end{pmatrix}
$$

---
 
#### Comprobando

 $$
(AB)C = \begin{pmatrix} 
4 & 16 \\
10 & 34  \end{pmatrix}, \qquad
A(BC) = \begin{pmatrix} 
4 & 16 \\
10 & 34  \end{pmatrix}
$$

 Podemos observar que ambas matrices son iguales, por lo tanto podemos confirmar que son iguales:     **(AB)C = A(BC)**



  

---
