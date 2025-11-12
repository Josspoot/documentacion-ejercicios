# documentacion-ejercicios
# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Poot Mateo Josué Enmanuel
## Actividad \#16 - Matrices doc

---
### === Comentarios dentro del README ===
### Identificación de matrices 
<!-- Se identifican distintos tipos de matrices según sus propiedades -->
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
<!-- Se declaran las matrices A y B con las que se harán operaciones -->
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
<!-- Se realiza la suma elemento a elemento -->
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
<!-- Se multiplica la matriz A por 2 y luego se le resta la matriz B -->
$$ 
2A - B = 2
\begin{pmatrix} 
2 & -1 \\ 
3 & 4 \\ 
\end{pmatrix} 
-\begin{pmatrix} 
5 & 2 \\ 
-1 & 3 \\ 
\end{pmatrix} 
$$ 
<!-- Aquí se calcula 2A -->
$$ 
2A = \begin{pmatrix} 
4 & -2 \\ 
6 & 8 \\ 
\end{pmatrix} 
$$ 
<!-- Finalmente se resta 2A - B -->
$$ 2A - B = \begin{pmatrix} 
4 & -2 \\ 
6 & 8 \\ 
\end{pmatrix} 
-\begin{pmatrix} 
5 & 2 \\ 
-1 & 3 \\ 
\end{pmatrix} 
=\begin{pmatrix} 
-1 & -4 \\ 
7 & 5 \\ 
\end{pmatrix} 
$$

---

### c) Producto \( AB \)
<!-- Se realiza la multiplicación de A por B aplicando la regla fila x columna -->
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

<!-- Se desarrolla el cálculo de cada posición de la matriz -->
$$
AB =
\begin{pmatrix}
(2)(5)+ (-1)(-1) | & (2)(2)+ (-1)(3) \\
(3)(5)+ (4)(-1) | & (3)(2)+ (4)(3) \\
\end{pmatrix}
$$  

<!-- Resultado final del producto AB -->
$$
AB =
\begin{pmatrix}
11 & 1 \\
11 & 18 \\
\end{pmatrix}
$$

---

### d) Producto \( BA \)
<!-- Ahora se invierte el orden de multiplicación para comparar resultados -->
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

<!-- Se desarrolla el cálculo de cada posición -->
$$
BA =
\begin{pmatrix}
(5)(2)+ (2)(3) | & (5)(-1)+ (2)(4) \\
(-1)(2)+ (3)(3) | & (-1)(-1)+ (3)(4) \\
\end{pmatrix}
$$  

<!-- Resultado final del producto BA -->
$$
BA =
\begin{pmatrix}
16 & 3 \\
7 & 13 \\
\end{pmatrix}
$$ 

---

### e) Transpuesta de \( A \)
<!-- Se intercambian las filas por columnas -->
$$
A^T =
\begin{pmatrix}
2 & 3 \\
-1 & 4 \\
\end{pmatrix}
$$  

---

# EJERCICIO 3: Multiplicación de cadena
<!-- Se verifica la propiedad asociativa: (AB)C = A(BC) -->
### matrices:
<!-- Se definen tres matrices A, B y C -->
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

<!-- Paso a paso para comprobar la igualdad -->
Verifica que (AB)C = A(BC)

(AB)C
<!-- Se multiplica A por B primero -->
$$ AB =
\begin{pmatrix}
2 & 0 \\
2 & 6 \\
---- & ---- \\
6 & 0 \\
4 & 12 \\
\end{pmatrix}
$$

<!-- Resultado simplificado de AB -->
$$ AB =
\begin{pmatrix}
4 & 6 \\
10 & 12 \\
\end{pmatrix}
$$

<!-- Luego se multiplica el resultado por C -->
$$ (AB)C =
\begin{pmatrix}
4 & 4 \\
0 & 12 \\
---- & ---- \\
10 & 10 \\
0 & 24 \\
\end{pmatrix}
$$

<!-- Resultado final de (AB)C -->
$$ (AB)C =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

<!-- Se repite el proceso, pero primero B*C -->
A(BC)

<!-- Se multiplica B por C -->
$$ BC =
\begin{pmatrix}
2 & 2 \\
0 & 0 \\
---- & ---- \\
1 & 1 \\
0 & 6 \\
\end{pmatrix}
$$

<!-- Resultado simplificado de BC -->
$$ BC =
\begin{pmatrix}
2 & 2 \\
1 & 7 \\
\end{pmatrix}
$$

<!-- Se multiplica ahora A por el resultado BC -->
$$ a(BC) =
\begin{pmatrix}
2 & 2 \\
2 & 14 \\
---- & ---- \\
6 & 6 \\
4 & 28 \\
\end{pmatrix}
$$

<!-- Resultado final de A(BC) -->
$$ A(BC) =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

<!-- Conclusión: se verifica que son iguales -->
(AB)C = A(BC) son iguales

