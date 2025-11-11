# 📘 Fundamentos de álgebra - Práctica 1

## 👨‍💻 Información del Estudiante

- **Nombre:** Astrit Airan Cetzal Cetzal
- **Matrícula:** SW2509028
- **Grupo:** C
- **Cuatrimestre:** Primer Cuatrimestre
- **Carrera:** TSU en Desarrollo e Innovación de Software
- **Profesor:** Jorge Javier Pedrozo Romero

---

## 📋 Descripción del Proyecto

Este repositorio contiene mi solución a la práctica de **Fundamentos de álgebra**, donde implemento funciones en JavaScript para resolver problemas de álgebra básica, preparándome para trabajar con operaciones matriciales más complejas.

## 🎯 Objetivos Alcanzados

- ✅ Dominar variables y tipos de datos en JavaScript
- ✅ Implementar estructuras condicionales
- ✅ Utilizar bucles y funciones
- ✅ Manipular arrays unidimensionales
- ✅ Trabajar con arrays bidimensionales (matrices)
- ✅ Aplicar control de versiones con Git y GitHub

---

## 📊 Progreso de Ejercicios

### Sección 1: Variables y Tipos de Datos (10 pts)
- [x] 1.1 Mi Información (2 pts) ✅
- [x] 1.2 Operaciones Básicas (3 pts) ✅
- [x] 1.3 Área de Rectángulo (2 pts) ✅
- [x] 1.4 Conversión Celsius a Fahrenheit (3 pts) ✅

**Puntos obtenidos: 10/10**

### Sección 2: Condicionales (15 pts)
- [x] 2.1 Par o Impar (3 pts) ✅
- [x] 2.2 Evaluar Nota (4 pts) ✅
- [x] 2.3 Mayor de Tres (4 pts) ✅
- [x] 2.4 Clasificar Edad (4 pts) ✅

**Puntos obtenidos: 15/15**

### Sección 3: Funciones y Bucles (20 pts)
- [x] 3.1 Factorial (5 pts) ✅
- [x] 3.2 Suma Hasta N (4 pts) ✅
- [x] 3.3 Tabla de Multiplicar (5 pts) ✅
- [x] 3.4 Números Pares (6 pts) ✅

**Puntos obtenidos: 20/20**

### Sección 4: Arrays (25 pts)
- [x] 4.1 Suma de Array (4 pts) ✅
- [x] 4.2 Promedio de Array (5 pts) ✅
- [x] 4.3 Encontrar Máximo (6 pts) ✅
- [x] 4.4 Filtrar Mayores (5 pts) ✅
- [x] 4.5 Invertir Array (5 pts) ✅

**Puntos obtenidos: 25/25**

### Sección 5: Arrays Bidimensionales - Matrices (30 pts)
- [x] 5.1 Crear Matriz (6 pts) ✅
- [x] 5.2 Suma de Matriz (6 pts) ✅
- [x] 5.3 Obtener Fila (5 pts) ✅
- [x] 5.4 Obtener Columna (7 pts) ✅
- [x] 5.5 Transponer Matriz (6 pts) ✅

**Puntos obtenidos: 30/30**

---

## 📈 Calificación Final

```
┌────────────────────────────────────────┐
│  REPORTE DE CALIFICACIÓN               │
├────────────────────────────────────────┤
│  Puntos obtenidos: 100/100             │
│  Porcentaje: 100%                      │
│  🎓 Calificación: A - Excelente        │
└────────────────────────────────────────┘
```

![Tests](../../actions/workflows/test.yml/badge.svg)

---

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- Git

### Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/fundamentos-programacion-practica-1.git
cd fundamentos-programacion-practica-1
```

### Instalar dependencias
```bash
npm install
```

### Ejecutar tests
```bash
npm test
```

### Ejecutar tests en modo watch
```bash
npm run test:watch
```

### Ver cobertura de código
```bash
npm run test:coverage
```

---

## 📁 Estructura del Proyecto

```
fundamentos-programacion-practica-1/
│
├── ejercicios.js           # ⭐ Archivo principal con mis soluciones
├── ejercicios.test.js      # Tests automatizados (no modificar)
├── package.json            # Configuración del proyecto
├── README.md               # Este archivo
├── GUIA_ESTUDIANTES.md     # Guía de referencia
├── GUIA_INSTRUCTOR.md      # Guía del profesor
│
└── .github/
    └── workflows/
        └── test.yml        # Configuración de GitHub Actions
```

---

## 💡 Aprendizajes Clave

### Lo que más me costó
- **Ejercicio 5.1 (Crear Matriz)**: Visualizar como debia usar los for para columnas y filas para que solo se agrgaran 0 a la matriz.
- **Ejercicio 5.2 (Suma Matriz)**:Entender la manera en la que debia usar los for, uno para recorrer filas, y el otro para recorrer columnas.
- **Ejercicio 5.4 (Obtener columna)**: Entender como utilizar el for para que solo se obtuvieran los elementos de alguna columna. 

### Lo que más me gustó
- **Arrays Bidimensionales**: Me gustó mucho trabajar con las matrices, porque aprendí al investigar como se hacia, y ya de ahi fui entendiendo las funciones.
- **Git Hub**: Aprender a usar Git hub y acerca de su imporatancia me parace bastante escencial para documentar nuestros códigos. 

### Técnicas aplicadas
- Uso de `for` loops para iteraciones
- Operador módulo `%` para determinar paridad
- Arrays dinámicos con `.push()`
- Bucles anidados para matrices
- Uso de Math
- Uso del .length
---

## 🔧 Ejemplos de Código

### Función Favorita: Crear Matriz
```javascript
function crearMatriz(filas, columnas) {
    const matriz = [];
    for (let i =0; i < filas; i++){
        const fila = [];
    
    for (let j =0; j < columnas; j++){
        fila.push(0);
    }
    matriz.push(fila);
    }
    return matriz;
}
```

**Por qué me gusta:** Crea una matriz de cualquier tamaño con solo agregar un numero para filas y otro para columnas. Para esta función solo se ponen 0s, pero si se modificara podrian aplicarse otros numero.
---

## 📚 Recursos Utilizados

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [JavaScript.info](https://es.javascript.info/)
- [Stack Overflow](https://stackoverflow.com)
- Guía del estudiante incluida en el repositorio

---

## 🎯 Próximos Pasos

Este proyecto me prepara para:
- ✨ Operaciones matriciales avanzadas (multiplicación, determinantes)
- 🖼️ Desarrollo de editores de imágenes
- 🔐 Implementación de algoritmos de encriptación
- 📊 Creación de calculadoras científicas

---

## 📝 Historial de Commits

```bash
# Ver mi historial completo
git log --oneline --graph --decorate
```
- Ejercicio 22 completado. transpone matriz.
- Ejercicio 21 completado, retorna la columna indicada.
- Ejercicio 20 completado, retorna la fila indicada
- Ejercicio 19 completado, suma elementos de una matriz
- Ejercicio 18 completado, crear matriz con solo 0s
- Ejercicio 17 completado, invierte el orden de los numeros ingresados
- Ejercicio 16 completado, filtra los numeros mayores
- Ejercicio 15 completado, devuelve el maximo
- Ejercicio 14 completado
- Ejercicio 13 completado
- Ejercicio 12 completado
- Ejercicio 11 completado correctamente
- Ejercicio 11 completado
- Ejercicio 10 completado
- Ejercicio 9 completado
- Ejercicio 8 completado
- Ejercicio 7 completado
- Ejercicio 6 completado
- Ejercicio 5 completado
- Ejercicio 4 completado
- Ejercicio 3 completado
- Ejercico 2 completado
- test


**Commits destacados:**
- `feat: Completar Sección 1 - Variables y tipos de datos`
- `feat: Implementar ejercicios de condicionales`
- `feat: Resolver funciones y bucles`
- `feat: Completar manipulación de arrays`
- `feat: Finalizar arrays bidimensionales - matrices`
- `docs: Actualizar README con resultados finales`

---

## 🤝 Agradecimientos

- **Profesor Jorge Javier Pedrozo Romero** por la estructura del curso, la práctica, y tambien por su apoyo en el proceso 
- **Compañeros del Grupo [B/C]** Venus Getsemaní Semino Alemán, Joaquín Uriona por el apoyo mutuo
- **Tecnológico de Software** por la formación integral

---

## 📧 Contacto

- **Email Institucional:** astrit.cetzal@tecdesoftware.edu.mx
- **GitHub:** [@astritcetzal](https://github.com/astritcetzal)

---

## 📄 Licencia

Este proyecto es parte de las actividades académicas del **Tecnológico de Software** y está bajo la licencia MIT.

---

<div align="center">

**⭐ Si te gustó este proyecto, dale una estrella ⭐**

Hecho con 💙 por Astrit Airan Cetzal Cetzal - 2025

</div>
