# Nodalis — Infraestructura de red empresarial

<div align="center">

  <img src="docs/images/logo.png" alt="Nodalis Logo" width="180">

  <h3 align="center">NODALIS</h3>

  <p align="center">
    Infraestructura informática y servicios de red empresarial
    <br />
    <br />
    <img src="https://img.shields.io/badge/Project-Final%20SMX-blue?style=for-the-badge" alt="Project">
    <img src="https://img.shields.io/badge/Course-2026--2027-informational?style=for-the-badge" alt="Course">
    <img src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge" alt="Status">
    <br />
    <br />
    **Biel Manjón · Marc Moreno**
    <br />
    Institut Puig Castellar
    <br />
    <br />
    <a href="https://tree.taiga.io/project/marcmorenoariza-nodalis/kanban"><strong>Project Board</strong></a>
  </p>

</div>

---

## Table of Contents

<details>
  <summary>View contents</summary>

  1. [About the Project](#about-the-project)
  2. [Project Objectives](#project-objectives)
  3. [Technologies](#technologies)
  4. [Repository Structure](#repository-structure)
  5. [Infrastructure](#infrastructure)
  6. [Workflow](#workflow)
  7. [Testing and Documentation](#testing-and-documentation)
  8. [Project Tracking](#project-tracking)
  9. [Project Status](#project-status)
  10. [Authors](#authors)

</details>

---

## About the Project

**Nodalis** is an academic project developed as part of the final project of the Microcomputer Systems and Networks (SMX) vocational training programme at Institut Puig Castellar.

The project focuses on designing, deploying and managing the IT infrastructure of a fictional company, simulating a real-world business environment.

The main purpose is to build an organized, secure and functional network infrastructure capable of managing users, devices, services and shared resources.

The implementation combines virtualization, network services, server administration and web development technologies.

## Project Objectives

The main objectives of the project are:

- Design and implement the company's network infrastructure.
- Configure IP addressing and network segmentation.
- Deploy DNS and DHCP services.
- Implement a firewall to control network traffic.
- Configure an Active Directory domain environment.
- Manage users, groups and access permissions.
- Set up shared folders and storage resources.
- Implement a backup system.
- Develop a corporate website using Astro.
- Perform functionality and security tests.

## Technologies

The following technologies and tools will be used throughout the project.

| Technology | Purpose |
|:---|:---|
| Virtual Machines | Server and workstation virtualization. |
| DNS | Domain and hostname resolution. |
| DHCP | Automatic IP address assignment. |
| Firewall | Network traffic filtering and security. |
| Active Directory | Centralized user and computer management. |
| Shared Folders | File storage and access management. |
| Backup System | Data protection and recovery. |
| Astro | Corporate website development. |
| Git / GitHub | Version control and collaboration. |

## Repository Structure

The repository is divided into several directories to keep the project organized and simplify maintenance.

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

*The repository structure may evolve throughout the development process.*

## Infrastructure

The Nodalis infrastructure is organized into several functional areas.

| Area | Description |
|:---|:---|
| Network | Network design, IP addressing and connectivity. |
| Network Services | DNS and DHCP configuration. |
| Security | Firewall and traffic management. |
| Servers | Virtualization and server administration. |
| User Management | Centralized administration through Active Directory. |
| Storage | Shared folders and access permissions. |
| Backups | Data protection and recovery. |
| Web Development | Corporate website built with Astro. |

## Workflow

Git and GitHub will be used to manage source code, track changes and coordinate collaboration between project members.

### Branch Strategy

| Branch | Purpose |
|:---|:---|
| `main` | Main branch containing stable versions. |
| `feature/<task>` | Branches dedicated to specific tasks and features. |

### Development Workflow

1. Create a new `feature/<task>` branch.
2. Implement the corresponding changes.
3. Commit the changes.
4. Push the branch to the remote repository.
5. Open a Pull Request targeting `main`.
6. Review and merge the changes.

### Repository Guidelines

- **Screenshots:** All evidence must be stored in a `capturas/` directory within its corresponding section.
- **Security:** Passwords, private keys and ISO files must never be uploaded.
- **Organization:** Files must be stored in their corresponding directories.
- **Stability:** The `main` branch must contain stable versions.
- **Collaboration:** Changes must be integrated through Pull Requests.

## Testing and Documentation

Throughout the project, configurations and tests will be documented to demonstrate that the infrastructure works correctly.

The evidence will include:

- Network configuration and connectivity.
- DNS and DHCP service functionality.
- Firewall configuration and traffic filtering.
- Active Directory users and groups.
- Shared folder access and permissions.
- Backup execution and verification.
- Corporate website functionality.

Screenshots and supporting documentation will be stored in their corresponding project directories.

## Project Tracking

Taiga will be used as the project's Kanban management tool to organize tasks, assign responsibilities and monitor development progress.

**Project Board:**

[Open Nodalis Kanban Board](https://tree.taiga.io/project/marcmorenoariza-nodalis/kanban)

## Project Status

![Status](https://img.shields.io/badge/Development-In%20Progress-orange?style=for-the-badge)

Nodalis is currently under development.

The infrastructure, services and documentation will be progressively implemented throughout the 2026/2027 academic year.

## Authors

| Name | Role |
|:---|:---|
| Biel Manjón | Project development |
| Marc Moreno | Project development |

**Institution:** Institut Puig Castellar  
**Programme:** Microcomputer Systems and Networks (SMX)  
**Academic Year:** 2026/2027

---

<div align="center">

  **NODALIS**

  *Designing and implementing enterprise IT infrastructure.*

<<<<<<< HEAD
Para mantener el repositorio organizado y evitar problemas durante el desarrollo, seguiremos unas normas básicas:

- **Capturas:** todas las imágenes y evidencias se guardarán en una carpeta `capturas/` dentro de su correspondiente apartado.
- **Seguridad:** no se subirán contraseñas, claves privadas ni archivos ISO al repositorio.
- **Ramas:** `main` será la rama principal y contendrá las versiones estables del proyecto.
- **Cambios:** cada integrante trabajará en su propia rama `feature/<tarea>` y después abrirá un Pull Request para incorporar los cambios.
- **Organización:** los archivos se guardarán siempre en la carpeta correspondiente para facilitar su localización.

---

## 5. Seguimiento del proyecto

Utilizaremos un tablero Kanban para organizar las tareas, controlar el progreso y saber qué queda pendiente.

🔗  [https://tree.taiga.io/project/marcmorenoariza-nodalis/kanban]

---

## 6. Evidencias y pruebas

Durante el desarrollo iremos añadiendo capturas de pantalla y comprobaciones para demostrar que los diferentes apartados funcionan correctamente.

Las evidencias incluirán, entre otras cosas:

- Configuración y funcionamiento de la red.
- Servicios DNS y DHCP.
- Configuración del firewall.
- Usuarios y grupos de Active Directory.
- Acceso a carpetas compartidas y permisos.
- Realización de copias de seguridad.
- Funcionamiento de la página web.

---

## 7. Estado del proyecto
<kbd>EN DESARROLLO</kbd>
=======
  <a href="#nodalis--infraestructura-de-red-empresarial">Back to top</a>
>>>>>>> 7b4684a (Readme Changes)

</div>
