# ExpenseTracker

Aplicación móvil para el control de finanzas personales, desarrollada con **Flutter y Dart**. Permite administrar ingresos y gastos, consultar movimientos financieros y visualizar el balance disponible.

El proyecto tiene como objetivo reforzar los fundamentos de programación mediante el desarrollo de una aplicación práctica, aplicando buenas prácticas de desarrollo y organización de código.

## Objetivos del proyecto

- Practicar los fundamentos del lenguaje Dart.
- Comprender la arquitectura y funcionamiento de Flutter.
- Aplicar programación orientada a objetos.
- Implementar operaciones CRUD.
- Trabajar con almacenamiento local mediante SQLite.
- Aprender a gestionar estados y navegación.
- Implementar validaciones y manejo de errores.
- Utilizar Git y GitHub para el control de versiones.

## Funcionalidades

### Gestión de movimientos
- Registrar ingresos.
- Registrar gastos.
- Consultar historial de movimientos.
- Editar movimientos existentes.
- Eliminar movimientos.
- Clasificar movimientos por categorías.

### Control financiero
- Consultar balance disponible.
- Calcular ingresos totales.
- Calcular gastos totales.
- Filtrar movimientos por categoría.
- Consultar estadísticas de gastos.

## Tecnologías

| Tecnología | Uso |
|---|---|
| Flutter | Framework de desarrollo móvil |
| Dart | Lenguaje de programación |
| Material 3 | Diseño de interfaz |
| SQLite | Almacenamiento local |
| sqflite | Integración de SQLite con Flutter |
| Git | Control de versiones |
| GitHub | Repositorio y seguimiento del proyecto |


## Modelo de datos

Cada movimiento financiero tendrá los siguientes atributos:

| Campo | Tipo | Descripción |
|---|---|---|
| id | Integer | Identificador único |
| type | String | Tipo de movimiento |
| description | String | Descripción |
| amount | Integer | Importe en centavos |
| category | String | Categoría |
| date | DateTime | Fecha del movimiento |

## Reglas de negocio

1. Los importes deben ser mayores que cero.
2. Todo movimiento debe tener una descripción.
3. Cada movimiento debe pertenecer a una categoría.
4. Los movimientos pueden ser ingresos o gastos.
5. El balance se calcula restando los gastos de los ingresos.
6. Los datos deben conservarse al cerrar la aplicación.

## Plan de desarrollo

El proyecto se desarrollará mediante un enfoque ágil, iterativo e incremental.

| Fase | Descripción | Estado |
|---|---|---|
| 1 | Inicialización y fundamentos de Dart | Pendiente |
| 2 | Modelo de datos y operaciones CRUD | Pendiente |
| 3 | Interfaz gráfica y navegación | Pendiente |
| 4 | Lógica financiera y cálculos | Pendiente |
| 5 | Persistencia con SQLite | Pendiente |
| 6 | Validaciones y pruebas | Pendiente |
| 7 | Documentación y publicación | Pendiente |

## Instalación y ejecución

### Requisitos

- Flutter SDK.
- Dart SDK (incluido con Flutter).
- Android Studio o Visual Studio Code.
- Git.


## Alcance inicial

La primera versión estará enfocada en las operaciones fundamentales de administración financiera y almacenamiento local.

No se contemplan inicialmente:
- Autenticación de usuarios.
- Sincronización en la nube.
- Integración con instituciones bancarias.
- Gestión de múltiples cuentas.
- Exportación de reportes.

## Propósito educativo

ExpenseTracker es un proyecto personal de aprendizaje orientado a fortalecer conocimientos de programación y desarrollo móvil.

Se priorizará la comprensión de la lógica, la implementación propia de funcionalidades, la resolución de problemas y la escritura de código limpio y mantenible.

## Autor

Creado por: Ruiz Campos Jose Fernando.
Desarrollado como proyecto personal de aprendizaje y práctica de ingeniería de software.


**ExpenseTracker — Controla tus movimientos. Comprende tus finanzas.**