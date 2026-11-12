# Infraestructura de red empresarial

<div align="center">

  <img src="docs/images/logo-readme-2.gif" alt="Logotipo de Nodalis" width="700">

  <p align="center">
    Diseño, implementación y administración de una infraestructura informática empresarial.
    <br />
    <br />
    <img src="https://img.shields.io/badge/Proyecto-Final%20SMX-blue?style=for-the-badge" alt="Proyecto Final SMX">
    <img src="https://img.shields.io/badge/Curso-2026--2027-informational?style=for-the-badge" alt="Curso 2026-2027">
    <img src="https://img.shields.io/badge/Estado-En%20desarrollo-orange?style=for-the-badge" alt="En desarrollo">
    <br />
    <br />
    Biel Manjón · Marc Moreno
    <br />
    Institut Puig Castellar
    <br />
    <br />
    <a href="https://tree.taiga.io/project/marcmorenoariza-nodalis/kanban"><strong>Consultar tablero del proyecto</strong></a>
  </p>

</div>

---

## Índice

<details>
  <summary>Ver contenido</summary>

  1. [Sobre el proyecto](#sobre-el-proyecto)
  2. [Objetivos](#objetivos)
  3. [Tecnologías utilizadas](#tecnologías-utilizadas)
  4. [Estructura del repositorio](#estructura-del-repositorio)
  5. [Infraestructura](#infraestructura)
  6. [Organización y metodología](#organización-y-metodología)
  7. [Pruebas y documentación](#pruebas-y-documentación)
  8. [Seguimiento del proyecto](#seguimiento-del-proyecto)
  9. [Estado del proyecto](#estado-del-proyecto)
  10. [Autores](#autores)

</details>

---

## Sobre el proyecto

**Nodalis** es un proyecto académico desarrollado como parte del Proyecto Final del ciclo formativo de Sistemas Microinformáticos y Redes (SMX) del Institut Puig Castellar.

El proyecto consiste en diseñar, implementar y administrar la infraestructura informática de una empresa ficticia, simulando un entorno tecnológico empresarial real.

El objetivo principal es construir una infraestructura de red organizada, segura y funcional, capaz de gestionar los diferentes equipos, usuarios, servicios y recursos de la organización.

Para ello, se trabajará con servidores, máquinas virtuales, servicios de red y herramientas de administración de sistemas, integrando todos los componentes en un entorno centralizado.

## Objetivos

Los principales objetivos del proyecto son:

- Diseñar e implementar la infraestructura de red de la empresa.
- Configurar el direccionamiento IP y la segmentación de la red.
- Instalar y configurar los servicios DNS y DHCP.
- Implementar un firewall para controlar y proteger las comunicaciones.
- Desplegar un entorno de Active Directory para la gestión centralizada.
- Crear y administrar usuarios, grupos y permisos de acceso.
- Configurar carpetas compartidas y recursos de almacenamiento.
- Implementar un sistema de copias de seguridad.
- Desarrollar una página web corporativa utilizando Astro.
- Realizar pruebas de funcionamiento y seguridad de toda la infraestructura.

## Tecnologías utilizadas

Durante el desarrollo del proyecto se utilizarán diferentes tecnologías y herramientas relacionadas con la administración de sistemas, redes y desarrollo web.

| Tecnología | Funcionalidad |
|:---|:---|
| Máquinas virtuales | Virtualización de equipos y servidores. |
| DNS | Resolución de nombres de dominio y equipos. |
| DHCP | Asignación automática de direcciones IP. |
| Firewall | Filtrado y control del tráfico de red. |
| Active Directory | Gestión centralizada de usuarios, grupos y equipos. |
| Carpetas compartidas | Almacenamiento y administración de recursos compartidos. |
| Copias de seguridad | Protección y recuperación de datos. |
| Astro | Desarrollo de la página web corporativa. |
| Git y GitHub | Control de versiones y trabajo colaborativo. |

## Estructura del repositorio

El repositorio está organizado en diferentes directorios para mantener todos los archivos del proyecto ordenados y facilitar su mantenimiento.

```text
NODALIS/
│
├── docs/
│   ├── planificacion/
│   ├── propuesta/
│   ├── documento-funcional/
│   ├── gantt/
│   ├── kanban/
│   ├── memoria/
│   └── defensa/
│
├── red/
│   ├── direccionamiento/
│   ├── dns/
│   ├── dhcp/
│   └── firewall/
│
├── servidores/
│   ├── virtualizacion/
│   ├── active-directory/
│   ├── usuarios/
│   ├── grupos/
│   └── carpetas-compartidas/
│
├── web/
│
├── pruebas/
│   ├── funcionamiento/
│   └── seguridad/
│
└── README.md
```

*La estructura del repositorio podrá ampliarse y modificarse conforme avance el desarrollo del proyecto.*

## Infraestructura

La infraestructura de Nodalis se divide en diferentes áreas funcionales que trabajarán conjuntamente para proporcionar los servicios informáticos de la empresa.

| Área | Descripción |
|:---|:---|
| Red | Diseño, direccionamiento IP y conectividad. |
| Servicios de red | Configuración de los servicios DNS y DHCP. |
| Seguridad | Protección de la infraestructura mediante firewall. |
| Servidores | Virtualización y administración de servidores. |
| Gestión de usuarios | Administración centralizada mediante Active Directory. |
| Almacenamiento | Carpetas compartidas y gestión de permisos. |
| Copias de seguridad | Protección y recuperación de la información. |
| Desarrollo web | Creación de la página web corporativa con Astro. |

## Organización y metodología

Para desarrollar el proyecto de forma organizada y facilitar el trabajo en equipo, utilizaremos Git y GitHub como herramientas principales de control de versiones.

### Gestión de ramas

Seguiremos una estructura de ramas para mantener estable el código principal del proyecto.

| Rama | Funcionalidad |
|:---|:---|
| `main` | Rama principal que contiene las versiones estables. |
| `feature/<tarea>` | Ramas destinadas al desarrollo de tareas o funcionalidades específicas. |

### Flujo de trabajo

1. Crear una nueva rama `feature/<tarea>`.
2. Realizar los cambios correspondientes.
3. Guardar los cambios mediante commits.
4. Subir la rama al repositorio remoto.
5. Crear un Pull Request hacia `main`.
6. Revisar e integrar los cambios.

### Normas del repositorio

- **Capturas:** todas las evidencias se guardarán en una carpeta `capturas/` dentro de su correspondiente apartado.
- **Seguridad:** no se subirán contraseñas, claves privadas ni archivos ISO.
- **Organización:** todos los archivos deberán estar almacenados en su directorio correspondiente.
- **Estabilidad:** la rama `main` contendrá únicamente versiones estables del proyecto.
- **Colaboración:** los cambios se incorporarán mediante Pull Requests.

## Pruebas y documentación

Durante el desarrollo se documentarán las configuraciones y comprobaciones realizadas para demostrar el correcto funcionamiento de la infraestructura.

Las evidencias incluirán:

- Configuración y conectividad de la red.
- Instalación y funcionamiento de los servicios DNS y DHCP.
- Configuración y comprobación del firewall.
- Creación y administración de usuarios y grupos en Active Directory.
- Acceso a carpetas compartidas y comprobación de permisos.
- Realización y verificación de copias de seguridad.
- Funcionamiento de la página web corporativa.

Todas las pruebas estarán acompañadas de sus correspondientes capturas y documentación cuando sea necesario.

## Seguimiento del proyecto

Para organizar las tareas, distribuir el trabajo y controlar el progreso, utilizaremos **Taiga** como herramienta de gestión mediante un tablero Kanban.

El tablero permitirá consultar las tareas pendientes, las que se encuentran en desarrollo y las que ya han sido completadas.

**Tablero de trabajo:**

[Acceder al tablero Kanban de Nodalis](https://tree.taiga.io/project/marcmorenoariza-nodalis/kanban)

## Estado del proyecto

![Estado del proyecto](https://img.shields.io/badge/Desarrollo-En%20curso-orange?style=for-the-badge)

Nodalis se encuentra actualmente en fase de desarrollo.

A lo largo del curso académico 2026/2027 se implementarán progresivamente los diferentes servicios, configuraciones y funcionalidades previstas, documentando los avances y verificando su correcto funcionamiento.

## Autores

Proyecto desarrollado por:

| Integrante | Participación |

|Biel Manjón | Diseño e implementación del proyecto.|
|Marc Moreno | Diseño e implementación del proyecto.|

**Centro educativo:** Institut Puig Castellar

**Ciclo formativo:** Sistemas Microinformáticos y Redes (SMX)

**Curso académico:** 2026/2027

---

<div align="center">

  **NODALIS**

  *Diseñando e implementando infraestructuras informáticas empresariales.*

  <a href="#nodalis--infraestructura-de-red-empresarial">Volver al principio</a>

</div>
