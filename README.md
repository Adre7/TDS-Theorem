Teorema del Discriminante Sincopado (TDS)
Autor: Dramoria Fecha: 2026-04-26Licencia: MIT
---
**1. Enunciado Formal** 
Sea la familia de ecuaciones cuadráticas dependientes de un parámetro "n":
(n + A)x^2 + (Bn + C)x + (Dn + E) = 0
donde "A, B, C, D, E ∈ ℝ" y "B^2 - 4D ≠ 0".
Definimos:
- "n_lineal": valor de "n" que anula el coeficiente de "x^2"- "n1, n2": raíces en "n" de Δ(n) = 0
Teorema (TDS)
Se cumple que:
n_lineal = n1 * n2
si y sólo si:
4A(D + E) = C^2 + A B^2
---
2. Demostración
Sea:
f(x,n) = (n + A)x^2 + (Bn + C)x + (Dn + E)
(a) Valor que hace lineal la ecuación
n + A = 0 → n_lineal = -A
---
(b) Discriminante como polinomio en n
Δ(n) = (Bn + C)^2 - 4(n + A)(Dn + E)
Coeficientes relevantes:
A2 = B^2 - 4DC0 = C^2 - 4AE
Por Viète:
n1 * n2 = (C^2 - 4AE) / (B^2 - 4D)
---
(c) Condición de coincidencia
-A = (C^2 - 4AE) / (B^2 - 4D)
Multiplicando:
-A(B^2 - 4D) = C^2 - 4AE
Desarrollando:
-AB^2 + 4AD = C^2 - 4AE
Reordenando:
4AD + 4AE = C^2 + AB^2
4A(D + E) = C^2 + AB^2
Esto prueba la equivalencia. ∎
---
3. Ejemplo
(n + 2)x^2 + 6n x + 9 = 0
Parámetros:
A = 2, B = 6, C = 0, D = 0, E = 9
Verificación:
4A(D + E) = 72C^2 + AB^2 = 72
Se cumple.
Raíces del discriminante:
n1 = 2, n2 = -1
Producto:
n1 * n2 = -2 = n_lineal
---
4. Interpretación
Cuando se cumple:
4A(D + E) = C^2 + AB^2
la degeneración de grado coincide con la estructura del discriminante.
---
5. Dominio de Validez
El teorema requiere:
- "B^2 - 4D ≠ 0"- Coeficientes reales
Casos como "A = 0" reducen el contenido pero no lo contradicen.
---
6. Licencia
MIT License.
