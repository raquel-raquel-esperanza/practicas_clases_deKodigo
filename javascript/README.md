# 📘 Guía de Ejercicios Básicos de JavaScript

Bienvenido a esta **guía práctica de JavaScript**.  
Estos ejercicios están diseñados para practicar los **conceptos fundamentales del lenguaje**.

---

## 🎯 Objetivos

Practicar:

- Variables (`let`, `const`)
- Operaciones aritméticas
- Condicionales (`if`, `else`, `switch`)
- Bucles (`for`, `while`)
- Uso de `console.log`
- Lógica básica de programación

---

# 🧩 Ejercicio 01  
## Mi primera presentación

**Temas:** `variables` `let` `const` `console.log`

### 📋 Instrucción

Declara una constante llamada **nombre** con tu nombre y una variable llamada **edad** con tu edad.

Luego usa `console.log()` para imprimir un mensaje de presentación que incluya ambos valores.

---

### 💻 Código de inicio

```javascript
// Declara tus variables aquí
const nombre = ____;
let edad = ____;

// Imprime el mensaje de presentación
console.log(____);
```

---

### ✅ Salida esperada

```
Hola, mi nombre es Ana y tengo 22 años.
```

---

### 💡 Pista

Puedes usar **template literals**:

```javascript
console.log(`Hola, mi nombre es ${nombre} y tengo ${edad} años.`);
```

---

# 🧩 Ejercicio 02  
## Calculadora de precio con descuento

**Temas:** `variables` `const` `operaciones aritméticas`

### 📋 Instrucción

Declara una constante **precioOriginal** con valor `150`.

Declara una constante **descuento** con valor `20` (20%).

Calcula el **precio final** después del descuento.

---

### 💻 Código de inicio

```javascript
const precioOriginal = 150;
const descuento = 20; // porcentaje

// Calcula el monto del descuento
const montoDescuento = ____;

// Calcula el precio final
const precioFinal = ____;

console.log(`Precio original: $${precioOriginal}`);
console.log(`Descuento (${descuento}%): $${montoDescuento}`);
console.log(`Precio final: $${precioFinal}`);
```

---

### ✅ Salida esperada

```
Precio original: $150
Descuento (20%): $30
Precio final: $120
```

---

### 💡 Pista

```
(precioOriginal * descuento) / 100
```

---

# 🧩 Ejercicio 03  
## ¿Es mayor de edad?

**Temas:** `if` `else` `comparación`

### 📋 Instrucción

Declara una variable **edad**.

Usa una estructura `if / else` para determinar si la persona es **mayor de edad (18+)**.

---

### 💻 Código de inicio

```javascript
let edad = 16; // Cambia este valor para probar

if (____) {
  console.log('La persona es mayor de edad.');
} else {
  console.log('La persona es menor de edad.');
}
```

---

### ✅ Salida esperada

```
Si edad = 16
La persona es menor de edad
Si edad = 20
La persona es mayor de edad
```

---

# 🧩 Ejercicio 04  
## Clasificador de notas

**Temas:** `if` `else if` `else`

### 📋 Instrucción

Declara una variable **nota** del `0 al 10`.

Clasifícala según esta tabla:

| Nota | Resultado |
|-----|-----|
| 9 – 10 | Excelente |
| 7 – 8 | Bueno |
| 5 – 6 | Regular |
| 0 – 4 | Reprobado |

---

### 💻 Código de inicio

```javascript
let nota = 7;

if (nota >= 9) {
  console.log(____);
} else if (____) {
  console.log('Bueno');
} else if (____) {
  console.log(____);
} else {
  console.log(____);
}
```

---

### ✅ Salida esperada

```
Si nota = 7
Bueno
Si nota = 10
Excelente
Si nota = 3
Reprobado
```

---

# 🧩 Ejercicio 05  
## Día de la semana

**Temas:** `switch`

### 📋 Instrucción

Declara una variable **dia** del `1 al 7`.

| Número | Día |
|------|------|
|1|Lunes|
|2|Martes|
|3|Miércoles|
|4|Jueves|
|5|Viernes|
|6|Sábado|
|7|Domingo|

Si no está entre `1–7`, mostrar **"Día inválido"**.

---

### 💻 Código de inicio

```javascript
let dia = 3;

switch (dia) {
  case 1:
    console.log('Lunes');
    break;

  case 2:
    console.log(____);
    break;

  case 3:
    console.log(____);
    break;

  // Completa los casos restantes

  default:
    console.log(____);
}
```

---

### ✅ Salida esperada

```
Si dia = 3
Miércoles
Si dia = 7
Domingo
Si dia = 9
Día inválido
```

---

# 🧩 Ejercicio 06  
## Contando hasta 10

**Temas:** `for`

### 📋 Instrucción

Usa un **bucle for** para imprimir los números del **1 al 10**.

---

### 💻 Código de inicio

```javascript
for (let i = ____; i <= ____; i++) {
  console.log(i);
}
```

---

### ✅ Salida esperada

```
1
2
3
4
5
6
7
8
9
10
```

---

# 🧩 Ejercicio 07  
## Suma acumulada

**Temas:** `for` `acumulador`

### 📋 Instrucción

Usa un bucle `for` para sumar los números **del 1 al 100**.

---

### 💻 Código de inicio

```javascript
let suma = 0;

for (let i = 1; i <= 100; i++) {
  suma = ____;
}

console.log(`La suma de 1 a 100 es: ${suma}`);
```

---

### ✅ Salida esperada

```
La suma de 1 a 100 es: 5050
```

---

### 💡 Pista

```
suma = suma + i;
```

o

```
suma += i;
```

---

# 🧩 Ejercicio 08  
## Cuenta regresiva

**Temas:** `while`

### 📋 Instrucción

Usa un **bucle while** para hacer una cuenta regresiva desde **5 hasta 1**.

---

### 💻 Código de inicio

```javascript
let contador = 5;

while (contador ____) {
  console.log(contador);
  contador = ____;
}

console.log('¡Despegue!');
```

---

### ✅ Salida esperada

```
5
4
3
2
1
¡Despegue!
```

---

# 🧩 Ejercicio 09  
## Números pares e impares

**Temas:** `for` `if / else`

### 📋 Instrucción

Recorre los números **del 1 al 15**.

Determina si cada número es **par o impar**.

---

### 💻 Código de inicio

```javascript
for (let i = 1; i <= 15; i++) {
  if (i % 2 === 0) {
    console.log(____);
  } else {
    console.log(____);
  }
}
```

---

### ✅ Salida esperada

```
1 - impar
2 - par
3 - impar
4 - par
...
15 - impar
```

---

### 💡 Pista

El operador **módulo `%`** devuelve el residuo.

```
i % 2 === 0
```

---

# 🧩 Ejercicio 10  
## Tabla de multiplicar

**Temas:** `for` `const`

### 📋 Instrucción

Declara una constante **numero** y muestra su **tabla de multiplicar del 1 al 10**.

---

### 💻 Código de inicio

```javascript
const numero = 7;

console.log(`--- Tabla del ${numero} ---`);

for (let i = 1; i <= 10; i++) {
  const resultado = ____;
  console.log(____);
}
```

---

### ✅ Salida esperada

```
--- Tabla del 7 ---
7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
7 x 4 = 28
7 x 5 = 35
7 x 6 = 42
7 x 7 = 49
7 x 8 = 56
7 x 9 = 63
7 x 10 = 70
```

---

### 💡 Pista

```
numero * i
```

Ejemplo:

```
`${numero} x ${i} = ${resultado}`
```

---