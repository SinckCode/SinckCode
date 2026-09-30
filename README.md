<h1 align="center">Ángel David Onesto Frías</h1>

<p align="center">
  <strong>Full Stack · DevOps · IoT</strong><br>
  Estudiante de Ingeniería de Software · México
</p>

<p align="center">
  <a href="https://angelonesto.com"><img src="https://img.shields.io/badge/angelonesto.com-0f1115?style=flat-square&logo=googlechrome&logoColor=00b4d8" alt="angelonesto.com"></a>
  <a href="https://astrocloud.dev"><img src="https://img.shields.io/badge/astrocloud.dev-0f1115?style=flat-square&logo=icloud&logoColor=00b4d8" alt="astrocloud.dev"></a>
  <a href="mailto:contacto@angelonesto.com"><img src="https://img.shields.io/badge/contacto@angelonesto.com-0f1115?style=flat-square&logo=maildotru&logoColor=00b4d8" alt="contacto@angelonesto.com"></a>
</p>

---

No solo escribo el código: también levanto y mantengo la infraestructura donde
corre. Mis proyectos no viven en un hosting — corren en un clúster que administro
yo, con su propio enrutamiento, su CI/CD y su observabilidad. Cuando algo se cae a
las 2 a.m., el que entra a los logs soy yo, y ahí es donde he aprendido lo que no
venía en ningún curso.

Me muevo entre tres mundos que para mí son el mismo: **software** que la gente
usa, **infraestructura** que lo sostiene, y **electrónica** que lo conecta con el
mundo físico.

## En qué ando ahora

- 🛠️ **[angelonesto.com](https://angelonesto.com)** — mi plataforma: portafolio 3D
  con Three.js, blog, cursos y panel de administración. Next.js 15 + NestJS 10 +
  MongoDB, con mensajería en tiempo real por Socket.IO.
- ☁️ **[astrocloud.dev](https://astrocloud.dev)** — mi marca de servicios:
  desarrollo a medida e infraestructura para negocios.

## Cómo lo sostengo

Virtualización propia, red segmentada y publicación sin abrir puertos al router.
No es un homelab de práctica: es producción, y todo lo de arriba corre ahí.

**El despliegue es mío también.** Un `push` a `main` dispara GitHub Actions, que
hace un `POST` a mi propia [**deploy-api**](https://github.com/SinckCode/deploy-api):
esa API identifica de qué proyecto se trata, corre el pipeline que le toca en la
máquina que le toca, y verifica el resultado al final. Los workflows no llevan
credenciales de mi red — solo un token.

Encima, observabilidad con Grafana + Loki + Promtail, y escaneos de seguridad con
OWASP ZAP en el pipeline.

## Proyectos

| Proyecto | Qué es | Stack |
|---|---|---|
| **[deploy-api](https://github.com/SinckCode/deploy-api)** | Mi CI/CD autoalojado: un `POST` por proyecto, pipelines declarados en JSON, ejecución local o por SSH | Node, Express |
| **[portafolioN](https://github.com/SinckCode/portafolioN)** | La plataforma de angelonesto.com: portafolio 3D, blog, cursos, admin | Next.js 15, NestJS, MongoDB, Three.js |
| **[WhatsUpEarth](https://github.com/SinckCode/whatsup-earth)** | Dashboard de eventos naturales del planeta con la API EONET de la NASA | React, Node, Docker, Terraform |
| **[Clima Aula](https://github.com/SinckCode/clima-web)** | Monitoreo ambiental de un aula en tiempo real: sensores → API → dashboard | ESP32, Express, MongoDB, React |
| **[Control de acceso IoT](https://github.com/SinckCode/api-control-acceso)** | RFID con ESP32, API REST y app multiplataforma | ESP32, Express, MySQL, .NET MAUI |
| **[MyGameShelf](https://github.com/SinckCode/MyGameShelf)** | App Android con arquitectura MVVM y API propia escrita en Swift | Kotlin, Jetpack Compose, Vapor |
| **[GameVault](https://github.com/SinckCode/gameVault)** | App nativa de macOS contra una API en Vapor sobre Docker | SwiftUI, Vapor, MySQL |
| **[LibreriaApi](https://github.com/SinckCode/LibreriaApi)** | API REST con autenticación JWT y su frontend | FastAPI, Python, React |
| **[CRECIBV](https://github.com/SinckCode/Crecibv)** | Sitio para una asociación civil de personas con discapacidad visual. Hecho sin cobrar | React, SCSS, Firebase |

El catálogo completo, con capturas y video de cada uno, está en
**[angelonesto.com/portafolio](https://angelonesto.com/portafolio)**.

## Stack

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000?style=flat-square&logo=threedotjs)
![Sass](https://img.shields.io/badge/Sass-cc6699?style=flat-square&logo=sass&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646cff?style=flat-square&logo=vite&logoColor=white)

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-e0234e?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000?style=flat-square&logo=express)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Vapor](https://img.shields.io/badge/Vapor-0d0d0d?style=flat-square&logo=swift)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio)

**Datos**

![MongoDB](https://img.shields.io/badge/MongoDB-47a248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479a1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-dc382d?style=flat-square&logo=redis&logoColor=white)

**Infraestructura y DevOps**

![Proxmox](https://img.shields.io/badge/Proxmox-e57000?style=flat-square&logo=proxmox&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-fcc624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7b42bc?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-000?style=flat-square&logo=ansible)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-f38020?style=flat-square&logo=cloudflare&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2b037a?style=flat-square&logo=pm2&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-f46800?style=flat-square&logo=grafana&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-d94f00?style=flat-square&logo=opnsense&logoColor=white)

**IoT y móvil**

![ESP32](https://img.shields.io/badge/ESP32-e7352c?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979d?style=flat-square&logo=arduino&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7f52ff?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-f05138?style=flat-square&logo=swift&logoColor=white)
![.NET MAUI](https://img.shields.io/badge/.NET_MAUI-512bd4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ed8b00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)

## Hablemos

- 🌐 [angelonesto.com](https://angelonesto.com) — portafolio, blog y cursos
- ☁️ [astrocloud.dev](https://astrocloud.dev) — ¿necesitas software o infraestructura para tu negocio?
- ✉️ contacto@angelonesto.com

<p align="center"><em>«Rompo cosas en casa para aprender a arreglarlas en producción.»</em></p>
