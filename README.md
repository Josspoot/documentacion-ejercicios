# documentacion-ejercicios
# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Poot Mateo Josué Enmanuel
## Actividad \#16 - Matrices doc

---
### Identificación de matrices

**Matriz identidad**, porque la diagonal está compuesta solo por unos y los demás elementos son ceros.  

$$        
A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$  

**Matriz diagonal**, porque solo los elementos de la diagonal principal son diferentes de cero.  

$$
B =
\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
$$  

**Matriz simétrica**, porque es igual a su transpuesta, es decir, \( A = A^T \).  

$$
C =
\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6 \\
\end{pmatrix}
$$  

**Matriz triangular superior**, porque todos los elementos debajo de la diagonal son ceros.  

$$
D =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6 \\
\end{pmatrix}
$$  

---
### Ejercicio 2  

$$
A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix},
\quad
B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$  

---

### a) Suma de matrices \( A + B \)

$$
A + B =
\begin{pmatrix}
2 + 5 & -1 + 2 \\
3 + (-1) & 4 + 3 \\
\end{pmatrix}
$$  

$$
A + B =
\begin{pmatrix}
7 & 1 \\
2 & 7 \\
\end{pmatrix}
$$  

---

### b) Operación \( 2A - B \)

$$
\text{Operación } (2A - B) \\
\begin{align*}
2A - B &= 
2\begin{pmatrix}
2 & -1 \\
3 & 4
\end{pmatrix}
-
\begin{pmatrix}
5 & 2 \\
-1 & 3
\end{pmatrix} 
\quad &\text{(Sustitución)} \\
\\
&= 
\begin{pmatrix}
4 & -2 \\
6 & 8
\end{pmatrix}
-
\begin{pmatrix}
5 & 2 \\
-1 & 3
\end{pmatrix}
\quad &\text{(Cálculo de } 2A\text{)} \\
\\
&=
\begin{pmatrix}
4-5 & -2-2 \\
6-(-1) & 8-3
\end{pmatrix}
\quad &\text{(Resta de elementos)} \\
\\
&=
\begin{pmatrix}
-1 & -4 \\
7 & 5
\end{pmatrix}
\quad &\text{(Resultado final)}
\end{align*}
$$


---

### c) Producto \( AB \)

$$
AB =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$  

$$
AB =
\begin{pmatrix}
(2)(5)+ (-1)(-1) | & (2)(2)+ (-1)(3) \\
(3)(5)+ (4)(-1) | & (3)(2)+ (4)(3) \\
\end{pmatrix}
$$  

$$
AB =
\begin{pmatrix}
11 & 1 \\
11 & 18 \\
\end{pmatrix}
$$

---

### d) Producto \( BA \)

$$
BA =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$  

$$
BA =
\begin{pmatrix}
(5)(2)+ (2)(3) | & (5)(-1)+ (2)(4) \\
(-1)(2)+ (3)(3) | & (-1)(-1)+ (3)(4) \\
\end{pmatrix}
$$  

$$
BA =
\begin{pmatrix}
16 & 3 \\
7 & 13 \\
\end{pmatrix}
$$ 

---

### e) Transpuesta de \( A \)

$$
A^T =
\begin{pmatrix}
2 & 3 \\
-1 & 4 \\
\end{pmatrix}
$$  


---

# EJERCICIO 3: Multiplicacion de cadena
 
### matrices:

$$ A =
\begin{pmatrix}
1 & 2 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
2 & 0 \\
1 & 3 \\
\end{pmatrix}
$$

$$ C =
\begin{pmatrix}
1 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

Verifica que (AB)C = A(BC)

(AB)C

$$ AB =
\begin{pmatrix}
2 & 0 \\
2 & 6 \\
---- & ---- \\
6 & 0 \\
4 & 12 \\
\end{pmatrix}
$$

$$ AB =
\begin{pmatrix}
4 & 6 \\
10 & 12 \\
\end{pmatrix}
$$

$$ (AB)C =
\begin{pmatrix}
4 & 4 \\
0 & 12 \\
---- & ---- \\
10 & 10 \\
0 & 24 \\
\end{pmatrix}
$$

$$ (AB)C =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

A(BC)

$$ BC =
\begin{pmatrix}
2 & 2 \\
0 & 0 \\
---- & ---- \\
1 & 1 \\
0 & 6 \\
\end{pmatrix}
$$

$$ BC =
\begin{pmatrix}
2 & 2 \\
1 & 7 \\
\end{pmatrix}
$$

$$ a(BC) =
\begin{pmatrix}
2 & 2 \\
2 & 14 \\
---- & ---- \\
6 & 6 \\
4 & 28 \\
\end{pmatrix}
$$

$$ A(BC) =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

(AB)C = A(BC) son iguales












