# Trabajo práctico N°2:

Bienvenid@ al repositorio del **Trabajo práctico Nª 2** para la asignatura de Programacion 3. En este proyecto el **Grupo 6** ha desarrollado un maquetado CSS aprovechando la Modularización, centrado en la visualizacion, las pseudo-clases para la aplicacion de algunos efectos a lo largo de la pagina.

Github Pages: https://julianriedinger7.github.io/tp2_cine_2026_grupo6/

## 👥 Integrantes - Grupo 6
* **Alejandro Lucas Baldres**
* **Marianela Belardinelli**
* **Julieta Dabús**
* **Matías F. Ledesma González**
* **Julian Riedinger**
* **Clara Zivano**

## 📋 Organización
### Division del Trabajo
#### HTML
* INDEX.HTML > Julian Riedinger
* LOGIN.HTML > Marianela Belardinelli
* REGISTRO.HTML > Clara Zivano
* ESTRENOS.HTML > Julieta Dabús
* PERFIL.HTML > Matías F. Ledesma
* DETALLES.HTML > Alejandro Lucas Baldres

### CSS
* POSTER.CSS > Julieta Dabús
* NAV.CSS Y FOOTER.CSS > Julian Riedinger
* BUTTONS.CSS Y DETALLE.CSS> Alejandro Lucas Baldres
* CARD-HORIZONTAL.CSS Y CARD-VERTICAL.CSS > Clara Zivano
* INPUT.CSS > Marianela Belardinelli
* CSS ASOCIADO A PERFIL > Matías F. Ledesma

### METODOLOGIA DE USO DE GIT
Esta sección define el flujo de trabajo y las convenciones de nomenclatura para la gestión de ramas en los proyectos de desarrollo, asegurando un historial limpio y una integración controlada a través de GitHub.

#### Estructura de Ramas Principales
El proyecto se rige por dos ramas estables de larga duración:
    • Main: Es la rama principal del proyecto. Contiene el MVP (Minimum Viable Product) o la versión lista para entregar. Solo debe recibir código que haya sido probado y aprobado.
    • Dev: Es la rama de integración. Aquí se consolidan todas las funcionalidades y correcciones antes de pasar a la rama principal. Es el entorno de desarrollo activo.

#### Convenciones para Ramas Personales
Cada integrante del grupo trabajará en ramas creadas a partir de Dev. El nombre de estas ramas debe seguir una estructura específica según el propósito de la tarea:
* A. Nuevas Funcionalidades (Features)
> Si la tarea consiste en agregar una nueva característica o componente al proyecto:
    • Formato: feature/agregado-Iniciales
    • Ejemplo: feature/index.html-JR

* B. Corrección de Errores (Fixes)
> Si la tarea consiste en solucionar un error o realizar un ajuste técnico:
    • Formato: fix/correccion-Iniciales
    • Ejemplo: fix/correccionTags-CZ

#### 3. Proceso de Integración
Para mantener la integridad del código, queda estrictamente prohibido realizar un merge directo entre ramas locales.
    1. Pull Request (PR): Toda integración de una rama personal hacia Dev, o de Dev hacia Main, debe realizarse mediante un Pull Request a través de la interfaz de GitHub.
    2. Revisión: Los integrantes haran revisiones del codigo antes de que el compañero mergeé la rama. Esto asegura que se cumplan los estándares del proyecto antes de la unión final.

#### 4. Resumen de Flujo de Trabajo
    1. Estar posicionado en Dev y hacer un git pull para tener lo último.
    2. Crear la rama personal: git checkout -b feature/mi-tarea-AB.
    3. Realizar los cambios y hacer commit.
    4. Subir la rama al repositorio remoto: git push –set-upstream origin feature/mi-tarea-AB.
    5. Abrir el Pull Request en GitHub hacia la rama Dev.
    6. Realizar el Merge a la rama Dev
    7. Una vez que el codigo de Dev este estabilizado y listo para generar el entregable se deberá Realizar el Pull Request a Main


