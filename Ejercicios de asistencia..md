

# Tecnológico de Software

## Materia: Fundamentos de Álgebra

### Alumno: Manuel Jesus Tello May

### Grupo: 1B.

### Actividad #16 - Matrices

### Profesor: Jorge Pedrozo.
---

## 1. Identificación de matrices

**Matriz identidad**, porque la diagonal está compuesta solo por unos y los elementos fuera de la diagonal son ceros.

$$
A =
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
$$

---
**Matriz diagonal**, porque los elementos fuera de la diagonal son 0

$$
B =
\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0\\
0 & 0 & 5
\end{pmatrix}
$$ 

---

**Matriz simétrica**, porque los elementos respecto a la diagonal son idénticos.

$$
C =
\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5\\
4& 5 & 6
\end{pmatrix}
$$

---
**Matriz triangular superior**, porque los elementos debajo de la diagonal son 0.

$$
D =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5\\
0 & 0 & 6
\end{pmatrix}
$$

---
## 2. Operaciones con matrices.

**Suma de A y B:**

$$
A =
\begin{pmatrix}
2 & -1 \\
3 & 4 
\end{pmatrix}
$$

$$
B =
\begin{pmatrix}
5 & 2  \\
-1 & 3 
\end{pmatrix}
$$

La suma de matrices del mismo tamaño se realiza **sumando cada elemento correspondiente**:

$$
A + B =
\begin{pmatrix}
2 + 5 & -1 + 2\\
3 + (-1) & 4 + 3
\end{pmatrix}
$$

$$
A + B =
\begin{pmatrix}
6 & 1 \\
2 & 7 
\end{pmatrix}
$$

---
**Resta de 2A - B**

La resta de matrices del mismo tamaño se realiza **restando cada elemento correspondiente  de ambas matrices**:

$$
2A =
\begin{pmatrix}
2(2)  & -1 + 2 \\
3 (2) & 4 (2)
\end{pmatrix}
$$

$$
2A =
\begin{pmatrix}
4  & -2 \\
6 & 8
\end{pmatrix}
$$

$$
2A-B =
\begin{pmatrix}
4-5  & -2 -2 \\
-1 -6& 8-3
\end{pmatrix}
$$

$$
2A-B =
\begin{pmatrix}
-1  & -4 \\
-7 & 5
\end{pmatrix}
$$

---
**Multiplicación de AB**

La multiplicación de matrices del mismo tamaño se realiza **dividiendo cada elemento de la primera matriz por los dos primeros elementos de la segunda matriz y despues por los otros elementos siguientes (se toman como columnas)**:


AB = 2(5) + -1(-1) = 10 + 1 = 11
AB = 2(2) + -1(3) = 4 + (-3) = -12
AB = 3(5) + 4(-1) = 15 + (-4) = 11
AB = 3(2) + 4(3) = 6 + 12 = 18

$$
AB =
\begin{pmatrix}
11  & -12 \\
11 & 18
\end{pmatrix}
$$

---
**Multiplicación de BA**

BA = 5(2) + 2(3) = 10 + 6 = 16
BA = 5(-1) + 2(4) = -5 + 8 = 3
BA = -1(2) + 3(3) = -2 + 9 = 7
BA = -1(-1) + 3(4) = 1 + 12 = 13

$$
BA =
\begin{pmatrix}
16  & 3 \\
7 & 13
\end{pmatrix}
$$

---
**Transpuesta de A**

$$
A^T =
\begin{pmatrix}
2  & 3 \\
-1 & 4
\end{pmatrix}
$$

---
## 3. División de tres matrices.

$$
A =                                                                        
\begin{pmatrix}
1  & 2 \\
3 & 4
\end{pmatrix},                   
$$

$$
B =
\begin{pmatrix}
2  & 0 \\
1 & 3
\end{pmatrix}
$$

$$
C =
\begin{pmatrix}
1 & 1 \\
0 & 2
\end{pmatrix}
$$

----
**Resolver (AB)C = A(BC)**


AB = 1(2) + 2(1) = 2 + 2 = 4
AB = 1(0) + 2(3) = 0 + 6 = 6
AB = 3(2) + 4(1) = 6 + 4 = 10
AB = 3(0) + 4(3) = 0 + 12 = 12

$$
AB =
\begin{pmatrix}
4 &    6 \\
10 &  12
\end{pmatrix}
$$

----
**(AB)C**

(AB)C = 4(1) + 6(0) = 4 + 0 = 4
(AB)C = 4(1) + 6(2) = 4 + 12 = 16
(AB)C = 10(1) + 12(0) = 10 + 0 = 10
(AB)C = 10(1) + 12(2) = 10 + 24 = 34

$$
(AB)C =
\begin{pmatrix}
4 &    16 \\
10 &  34
\end{pmatrix}
$$

---
**BC**

BC = 2(1) + 0(0) =  2 + 0 = 2 
BC = 2(1) + 0(2) = 2 + 0= 2
BC = 1(1) + 3(0) = 1 + 0 = 1
BC = 1(1) + 3(2) = 1 + 6 = 7

$$
BC =
\begin{pmatrix}
2 &    2 \\
1 &  7
\end{pmatrix}
$$

---
**A(BC)**

A(BC) = 1(2) + 2(1) = 2 + 2 = 2
A(BC)  = 1(2) + 2(7) = 2 + 14 = 16
A(BC)  = 3(2) + 4(1) = 6 + 4 = 10
A(BC)  = 3(2) + 4(7) = 6 + 28 = 34

$$
A(BC) = 
\begin{pmatrix}
4 &   16 \\
10 &  34
\end{pmatrix}
$$

---
Con esto comprobamos que  **(AB)C = A(BC)** si son iguales.

$$
(AB)C =
\begin{pmatrix}
4 &    16 \\
10 &  34
\end{pmatrix}   =                                            
$$

$$
A(BC) = 
\begin{pmatrix}
4 &   16 \\
10 &  34
\end{pmatrix}
$$

---

