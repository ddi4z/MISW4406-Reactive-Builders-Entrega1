# 🏗️ Diseño y Construcción de Soluciones No Monolíticas

Este repositorio contiene la **primera entrega** del curso **MISW4406 - Diseño y Construcción de Soluciones No Monolíticas**. El trabajo se basa en el **Tutorial 1** del curso, utilizando la herramienta **ContextMapper** y fue desarrollado y probado en un entorno de **GitHub Codespaces**.

---

## 👥 Integrantes

| Nombre | Correo |
| :--- | :--- |
| Orlando Giovanny Solarte Delgado | o.solarte@uniandes.edu.co |
| Martín Flores Arango | r.floresa@uniandes.edu.co |
| Sara Sofía Cárdenas Rodríguez | ss.cardenas@uniandes.edu.co |
| Daniel Felipe Díaz Moreno | d.diazm@uniandes.edu.co |

---

## 📂 Estructura del Proyecto

La estructura del repositorio se organiza de la siguiente manera:

```
src/
├── main/
│   ├── cml/
│   │   ├── subdominios.cml
│   │   ├── contextosAsIs.cml
│   │   └── contextosToBe.cml
├── docs/
│   ├── lenguaje_ubicuo/
│   │   ├── as_is.jpg
│   │   └── to_be.jpg
│   └── contextos/
│       ├── as_is.png
│       └── to_be.png
```

- La carpeta **`src/main/cml/`** contiene el código fuente de los archivos **ContextMapper**.
- La carpeta **`src/docs/`** almacena todos los diagramas e imágenes generados.

A continuación, un desglose detallado de cada parte del proyecto.

### 1. Dominios y Subdominios

El archivo [src/main/cml/subdominios.cml](./src/main/cml/subdominios.cml) define los dominios y subdominios del proyecto **Alpes Partners** utilizando el lenguaje DSL de ContextMapper.

### 2. Event Storming y Lenguaje Ubicuo

En la carpeta [src/docs/lenguaje_ubicuo](./src/docs/lenguaje_ubicuo) se encuentran los diagramas de **Event Storming**, que ilustran el lenguaje ubicuo del sistema en los escenarios **AS-IS** (estado actual) y **TO-BE** (estado propuesto).

- [as_is.jpg](./src/docs/lenguaje_ubicuo/as_is.jpg)
- [to_be.jpg](./src/docs/lenguaje_ubicuo/to_be.jpg)

### 3. Contextos Acotados (Bounded Contexts)

El código fuente de los contextos acotados se encuentra en la carpeta [src/main/cml/](./src/main/cml/):

- [contextosAsIs.cml](./src/main/cml/contextosAsIs.cml)
- [contextosToBe.cml](./src/main/cml/contextosToBe.cml)

Sus representaciones gráficas en formato PNG se ubican en la carpeta [src/docs/contextos/](./src/docs/contextos/):

- [as_is.png](./src/docs/contextos/as_is.png)
- [to_be.png](./src/docs/contextos/to_be.png)