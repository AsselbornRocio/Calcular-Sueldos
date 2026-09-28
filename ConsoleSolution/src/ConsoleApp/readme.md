# 💼 Sistema de Cálculo de Sueldos

Este proyecto es una aplicación desarrollada en C# para calcular el sueldo de los empleados de una empresa aplicando distintas reglas de negocio, categorías y bonos[cite: 1].

---

## 📋 Consignas del Ejercicio

La fórmula general para calcular el sueldo es[cite: 1]:
$$\text{sueldo} = \text{neto} + \text{bonopresentismo} + \text{bonoresultado}$$

### Categorías y Sueldos Netos:
* **Gerente:** Sueldo neto $100.000[cite: 1]
* **Administrativo:** Sueldo neto $40.000[cite: 1]
* **Operador:** Sueldo neto $10.500[cite: 1]
* **Cadete:** Sueldo neto $1.000[cite: 1]

### Bonos por Presentismo:
* **Bono A:** 
  * $1.000 si el empleado no faltó nunca[cite: 1].
  * $450 si faltó 1 única vez[cite: 1].
  * $0 en cualquier otro caso[cite: 1].
* **Bono B:** 
  * Suma fija de $500[cite: 1].

### Bono por Resultados:
* 10% sobre el sueldo neto en caso de objetivo cumplido[cite: 1].
* $800 fijos en caso de cumplir el 80% del objetivo[cite: 1].
* $0 en cualquier otro caso[cite: 1].

---

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** C# y .NET
* **ORM:** Dapper