# 🚀 Curso de CI/CD para Estudiantes de Sistemas

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Made with](https://img.shields.io/badge/Made%20with-❤️-red.svg)]()
[![Level](https://img.shields.io/badge/Nivel-Intermedio-blue.svg)]()
[![Duration](https://img.shields.io/badge/Duración-16%20semanas-orange.svg)]()

> **Integración Continua y Entrega/Despliegue Continuo:** Domina las prácticas modernas de DevOps que están transformando la industria del software.

---

## 📚 Tabla de Contenidos

- [Acerca del Curso](#-acerca-del-curso)
- [Objetivos de Aprendizaje](#-objetivos-de-aprendizaje)
- [Prerrequisitos](#-prerrequisitos)
- [Stack Tecnológico](#️-stack-tecnológico)
- [Estructura del Curso](#-estructura-del-curso)
- [Temario Detallado](#-temario-detallado)
- [Proyectos Prácticos](#-proyectos-prácticos)
- [Metodología](#-metodología)
- [Evaluación](#-evaluación)
- [Recursos](#-recursos-adicionales)
- [Instalación del Entorno](#️-instalación-del-entorno)
- [Cómo Contribuir](#-cómo-contribuir)
- [Licencia](#-licencia)

---

## 🎯 Acerca del Curso

Este curso está diseñado para estudiantes de Ingeniería en Sistemas, Ciencias de la Computación e Informática que buscan introducirse en el mundo de **DevOps** mediante el dominio de las prácticas de **Integración Continua (CI)** y **Entrega/Despliegue Continuo (CD)**.

A lo largo de 16 semanas, los estudiantes aprenderán a automatizar el ciclo de vida del desarrollo de software, desde el commit hasta el despliegue en producción, utilizando las herramientas más demandadas por la industria actual.

### ¿Por qué CI/CD?

En el panorama actual del desarrollo de software, las empresas requieren entregar valor de forma rápida, confiable y segura. CI/CD es la columna vertebral que permite:

- ⚡ **Velocidad:** Despliegues múltiples por día en lugar de cada varios meses.
- 🛡️ **Calidad:** Detección temprana de errores mediante automatización.
- 🔄 **Confiabilidad:** Procesos repetibles y predecibles.
- 👥 **Colaboración:** Mejor integración entre equipos de desarrollo y operaciones.

---

## 🎓 Objetivos de Aprendizaje

Al finalizar este curso, el estudiante será capaz de:

1. Comprender los principios y la filosofía de **DevOps** y **CI/CD**.
2. Diseñar e implementar **pipelines** de integración y despliegue continuo.
3. Utilizar herramientas líderes como **Jenkins**, **GitHub Actions** y **GitLab CI**.
4. Aplicar principios de **Infraestructura como Código (IaC)** con Terraform y Ansible.
5. Containerizar aplicaciones usando **Docker** y orquestarlas con **Kubernetes**.
6. Implementar estrategias de **testing automatizado** en distintos niveles.
7. Configurar sistemas de **monitoreo, logging y observabilidad**.
8. Aplicar prácticas de **DevSecOps** integrando seguridad en el pipeline.
9. Gestionar **estrategias de despliegue** modernas (Blue/Green, Canary, Rolling).
10. Trabajar con metodologías **GitOps** y **Trunk-Based Development**.

---

## 📋 Prerrequisitos

### Conocimientos Técnicos
- Programación básica en al menos un lenguaje (Python, Java, JavaScript o similar).
- Fundamentos de **Git** y control de versiones.
- Conocimientos básicos de **línea de comandos** (Bash/PowerShell).
- Nociones de redes (HTTP, DNS, puertos).
- Comprensión básica de bases de datos relacionales.

### Hardware Recomendado
- CPU: 4 núcleos o superior.
- RAM: Mínimo 8 GB (recomendado 16 GB).
- Almacenamiento: 50 GB libres.
- Sistema operativo: Linux (preferido), macOS o Windows con WSL2.

### Cuentas Necesarias
- GitHub
- Docker Hub
- Cuenta gratuita en algún proveedor cloud (AWS Free Tier, GCP, Azure)

---

## 🛠️ Stack Tecnológico

| Categoría | Herramientas |
|-----------|--------------|
| **Control de Versiones** | Git, GitHub, GitLab, Bitbucket |
| **Servidores CI/CD** | Jenkins, GitHub Actions, GitLab CI, CircleCI, Travis CI |
| **Contenedores** | Docker, Podman, Buildah |
| **Orquestación** | Kubernetes, Docker Swarm, Helm |
| **Infraestructura como Código** | Terraform, Pulumi, AWS CloudFormation |
| **Gestión de Configuración** | Ansible, Chef, Puppet |
| **Testing** | JUnit, PyTest, Selenium, Cypress, JMeter, SonarQube |
| **Monitoreo** | Prometheus, Grafana, ELK Stack, Datadog |
| **Cloud Providers** | AWS, GCP, Azure |
| **Seguridad** | Trivy, Snyk, OWASP ZAP, HashiCorp Vault |
| **Artefactos** | Nexus, JFrog Artifactory, GitHub Packages |

---

## 📅 Estructura del Curso

El curso se divide en **4 módulos** distribuidos en **16 semanas**, con clases teórico-prácticas, laboratorios y proyectos integradores.

```
📦 Curso CI/CD
 ┣ 📂 Módulo 1: Fundamentos de DevOps y CI/CD (Semanas 1-4)
 ┣ 📂 Módulo 2: Integración Continua (Semanas 5-8)
 ┣ 📂 Módulo 3: Despliegue Continuo y Cloud (Semanas 9-12)
 ┗ 📂 Módulo 4: Observabilidad, Seguridad y Avanzado (Semanas 13-16)
```

---

## 📖 Temario Detallado

### 🔹 Módulo 1: Fundamentos de DevOps y CI/CD

#### Semana 1: Introducción a DevOps
- Historia y evolución de DevOps.
- La cultura DevOps: People, Process, Tools.
- Diferencia entre DevOps, SRE, Platform Engineering.
- Métricas DORA: Deployment Frequency, Lead Time, MTTR, Change Failure Rate.
- El ciclo de vida del desarrollo de software (SDLC).

#### Semana 2: Control de Versiones Avanzado con Git
- Repaso de comandos esenciales de Git.
- Estrategias de branching: Git Flow, GitHub Flow, Trunk-Based Development.
- Pull Requests, Code Reviews y Merge Strategies.
- Hooks de Git, rebase interactivo, cherry-pick.
- Resolución avanzada de conflictos.
- Conventional Commits y Semantic Versioning.

#### Semana 3: Fundamentos de CI/CD
- ¿Qué es Integración Continua?
- ¿Qué es Entrega Continua vs Despliegue Continuo?
- Pipelines como código.
- Anatomía de un pipeline: stages, jobs, steps.
- El concepto de "Shift Left" en testing y seguridad.
- Anti-patrones comunes en CI/CD.

#### Semana 4: Introducción a la Containerización
- Virtualización vs Containerización.
- Arquitectura de Docker: Engine, Images, Containers, Registries.
- Comandos esenciales de Docker.
- Dockerfiles: best practices y multi-stage builds.
- Docker Compose para entornos multi-servicio.
- Optimización de imágenes (Alpine, Distroless).

---

### 🔹 Módulo 2: Integración Continua

#### Semana 5: Jenkins
- Arquitectura de Jenkins: Master/Agent.
- Instalación y configuración inicial.
- Creación de jobs: Freestyle vs Pipeline.
- Jenkinsfile: Declarative vs Scripted Pipelines.
- Plugins esenciales y administración.
- Integración con Git y notificaciones.

#### Semana 6: GitHub Actions y GitLab CI
- Sintaxis YAML para workflows.
- Eventos, jobs, runners y matrices.
- Reutilización: composite actions y workflows reusables.
- Secrets y variables de entorno.
- GitLab CI: stages, runners, caché.
- Comparación entre plataformas CI/CD modernas.

#### Semana 7: Testing Automatizado
- Pirámide de testing: Unit, Integration, E2E.
- Test Driven Development (TDD) y Behavior Driven Development (BDD).
- Frameworks: JUnit, PyTest, Mocha, Jest.
- Mocking y stubs.
- Code Coverage con JaCoCo, Coverage.py, Istanbul.
- Tests de UI con Selenium y Cypress.

#### Semana 8: Calidad de Código y Análisis Estático
- Linters y formatters (ESLint, Pylint, Checkstyle).
- SonarQube: configuración y Quality Gates.
- Análisis SAST (Static Application Security Testing).
- Code smells, deuda técnica y refactoring.
- Pre-commit hooks con Husky y pre-commit.
- Documentación automática.

---

### 🔹 Módulo 3: Despliegue Continuo y Cloud

#### Semana 9: Infraestructura como Código (IaC)
- Principios de IaC: idempotencia, versionado, reproducibilidad.
- Terraform: providers, resources, state, modules.
- Workspaces y entornos múltiples.
- Variables, outputs y data sources.
- Terraform Cloud y backends remotos.
- Introducción a Pulumi y Ansible.

#### Semana 10: Kubernetes Fundamentals
- Arquitectura de Kubernetes: Control Plane y Workers.
- Objetos básicos: Pods, Deployments, Services, ConfigMaps, Secrets.
- Networking: Ingress, Network Policies.
- Storage: Volumes, PersistentVolumes, StorageClasses.
- Manejo de configuración y manifiestos YAML.
- Minikube, Kind y K3s para desarrollo local.

#### Semana 11: Helm y GitOps
- Helm: charts, templates, values, releases.
- Creación de charts personalizados.
- ArgoCD y Flux: GitOps en acción.
- Estrategia Pull-based vs Push-based deployment.
- Manejo declarativo de cluster state.
- Repositorios de configuración separados.

#### Semana 12: Estrategias de Despliegue
- Recreate, Rolling Update, Blue/Green, Canary.
- Feature Flags con LaunchDarkly, Unleash.
- A/B Testing en producción.
- Rollback strategies y database migrations.
- Service Mesh: Istio y Linkerd (introducción).
- Despliegue en AWS (ECS, EKS), GCP (GKE) y Azure (AKS).

---

### 🔹 Módulo 4: Observabilidad, Seguridad y Avanzado

#### Semana 13: Monitoreo y Observabilidad
- Los 3 pilares: Logs, Metrics, Traces.
- Prometheus: instalación, PromQL, alertas.
- Grafana: dashboards y visualizaciones.
- ELK Stack (Elasticsearch, Logstash, Kibana).
- Distributed Tracing con Jaeger y OpenTelemetry.
- SLOs, SLIs y Error Budgets.

#### Semana 14: DevSecOps
- Shift-left security en el pipeline.
- Análisis de vulnerabilidades en imágenes (Trivy, Grype).
- Dependency scanning (Snyk, Dependabot, Renovate).
- DAST (Dynamic Application Security Testing) con OWASP ZAP.
- Secrets management con HashiCorp Vault y AWS Secrets Manager.
- Compliance: SOC2, ISO 27001, GDPR considerations.
- Supply Chain Security: SBOM, SLSA, firmado con Cosign.

#### Semana 15: Pipelines Avanzados y Optimización
- Pipelines paralelos y matrices.
- Self-hosted runners y agentes ephemerals.
- Caching y artefactos.
- Reutilización de pipelines y plantillas.
- Pipeline orchestration con Argo Workflows y Tekton.
- Optimización de tiempos de build.
- Cost optimization en CI/CD.

#### Semana 16: Proyecto Final y Tendencias
- Presentación de proyectos finales.
- Platform Engineering e Internal Developer Platforms.
- Backstage como portal del desarrollador.
- AI/ML en CI/CD (AIOps).
- FinOps: gestión financiera en cloud.
- Tendencias 2026 y más allá.
- Carrera profesional en DevOps/SRE.

---

## 💻 Proyectos Prácticos

A lo largo del curso, los estudiantes desarrollarán proyectos progresivos que culminan en un sistema completo de CI/CD.

### Proyecto 1: Pipeline Básico (Módulo 1)
Construir una aplicación web simple (REST API) con un pipeline básico que compile, ejecute tests y empaquete una imagen Docker.

**Entregables:**
- Repositorio Git con buenas prácticas de branching.
- Dockerfile optimizado.
- Workflow de GitHub Actions funcional.

### Proyecto 2: CI Completo (Módulo 2)
Expandir el proyecto anterior agregando análisis de calidad, cobertura de código, tests de integración y publicación de artefactos.

**Entregables:**
- Tests unitarios con 80%+ de cobertura.
- Integración con SonarQube.
- Publicación automática a Docker Hub.
- Notificaciones en Slack/Discord.

### Proyecto 3: Despliegue en Kubernetes (Módulo 3)
Desplegar la aplicación en un cluster de Kubernetes con Helm, implementando una estrategia de despliegue Canary.

**Entregables:**
- Manifiestos de Kubernetes y Helm chart.
- Infraestructura provisionada con Terraform.
- ArgoCD configurado para GitOps.
- Pipeline de CD funcional con aprobaciones manuales.

### Proyecto Final: Plataforma DevOps Completa (Módulo 4)
Sistema integral con monitoreo, alertas, seguridad y observabilidad completa.

**Características requeridas:**
- ✅ Aplicación multi-servicio (frontend, backend, base de datos).
- ✅ Pipeline CI/CD completo desde commit hasta producción.
- ✅ Múltiples entornos (dev, staging, prod).
- ✅ Stack de monitoreo (Prometheus + Grafana).
- ✅ Logging centralizado.
- ✅ Análisis de seguridad automatizado.
- ✅ Documentación técnica completa.
- ✅ Runbooks y disaster recovery plan.

---

## 🎯 Metodología

El curso utiliza un enfoque **constructivista** y **práctico**, basado en:

- **Clases magistrales** (30%): Conceptos teóricos y fundamentos.
- **Laboratorios guiados** (40%): Práctica supervisada con instructor.
- **Trabajo autónomo** (20%): Proyectos individuales y en equipo.
- **Estudios de caso** (10%): Análisis de implementaciones reales.

### Herramientas de Aprendizaje
- 📺 Videos explicativos en plataforma LMS.
- 📝 Documentación interactiva.
- 🔬 Entornos sandbox preconfigurados.
- 💬 Foro de discusión y canal de Slack/Discord.
- 🎙️ Sesiones de pair programming.

---

## 📊 Evaluación

| Componente | Porcentaje |
|------------|-----------:|
| Laboratorios semanales | 25% |
| Proyectos parciales (3) | 30% |
| Examen parcial | 15% |
| Proyecto final | 25% |
| Participación y exposiciones | 5% |
| **Total** | **100%** |

### Criterios de Evaluación
- ✅ Funcionalidad correcta del pipeline.
- ✅ Calidad del código y documentación.
- ✅ Aplicación de buenas prácticas.
- ✅ Capacidad de troubleshooting.
- ✅ Justificación de decisiones técnicas.

---

## 📚 Recursos Adicionales

### 📖 Libros Recomendados
- *The Phoenix Project* – Gene Kim, Kevin Behr, George Spafford
- *Continuous Delivery* – Jez Humble, David Farley
- *The DevOps Handbook* – Gene Kim et al.
- *Accelerate* – Nicole Forsgren, Jez Humble, Gene Kim
- *Site Reliability Engineering* – Google
- *Kubernetes Up & Running* – Brendan Burns et al.

### 🌐 Sitios Web y Blogs
- [DevOps Roadmap](https://roadmap.sh/devops)
- [The New Stack](https://thenewstack.io/)
- [DevOps.com](https://devops.com/)
- [CNCF Landscape](https://landscape.cncf.io/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)

### 🎓 Certificaciones Sugeridas
- AWS Certified DevOps Engineer
- Certified Kubernetes Administrator (CKA)
- Certified Kubernetes Application Developer (CKAD)
- HashiCorp Certified: Terraform Associate
- Docker Certified Associate
- GitHub Actions Certification

### 📺 Canales de YouTube
- TechWorld with Nana
- DevOps Toolkit
- That DevOps Guy
- Bret Fisher Docker and DevOps

---

## ⚙️ Instalación del Entorno

### Requisitos previos
```bash
# Verificar versiones instaladas
git --version
docker --version
kubectl version --client
terraform --version
```

### Setup inicial
```bash
# Clonar el repositorio del curso
git clone https://github.com/usuario/curso-cicd.git
cd curso-cicd

# Instalar dependencias del entorno
./scripts/setup.sh

# Verificar instalación
make verify
```

### Estructura del Repositorio
```
curso-cicd/
├── modulo-1-fundamentos/
│   ├── semana-01/
│   ├── semana-02/
│   ├── semana-03/
│   └── semana-04/
├── modulo-2-ci/
├── modulo-3-cd/
├── modulo-4-avanzado/
├── proyectos/
│   ├── proyecto-1/
│   ├── proyecto-2/
│   ├── proyecto-3/
│   └── proyecto-final/
├── recursos/
│   ├── slides/
│   ├── cheatsheets/
│   └── lecturas/
├── scripts/
└── README.md
```

---

## 🤝 Cómo Contribuir

¡Las contribuciones son bienvenidas! Si encuentras errores, tienes sugerencias o quieres agregar contenido:

1. Haz fork del proyecto.
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`).
3. Haz commit de tus cambios (`git commit -m 'feat: agregar contenido sobre XYZ'`).
4. Push a la rama (`git push origin feature/AmazingFeature`).
5. Abre un Pull Request.

Por favor, lee [CONTRIBUTING.md](CONTRIBUTING.md) para más detalles sobre el código de conducta y el proceso de pull requests.

---

## 👨‍🏫 Equipo Docente

| Rol | Nombre | Contacto |
|-----|--------|----------|
| Profesor Titular | _Por definir_ | profesor@universidad.edu |
| Asistente Docente | _Por definir_ | asistente@universidad.edu |
| Coordinador de Lab | _Por definir_ | lab@universidad.edu |

---

## 📜 Licencia

Este material educativo está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

---

## ⭐ Agradecimientos

Agradecemos a la comunidad open source y a las siguientes organizaciones por sus recursos:
- Cloud Native Computing Foundation (CNCF)
- Linux Foundation
- DevOps Institute
- Comunidades locales de DevOps

---

<div align="center">

**¿Listo para comenzar tu viaje en DevOps? 🚀**

Hecho con ❤️ para la comunidad estudiantil de Sistemas

[⬆ Volver arriba](#-curso-de-cicd-para-estudiantes-de-sistemas)

</div>