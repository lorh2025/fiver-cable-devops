# Pruebas Unitarias e Integración
# Fiver Cable - Sistema de Gestión ISP & Cable TV

Este repositorio contiene la arquitectura de microservicios y la canalización de CI/CD para la empresa Fiver Cable.

## Estructura del Repositorio
- `/src`: Código fuente de los microservicios (usuarios, red, billing, soporte).
- `/docker`: Dockerfiles y archivos de configuración de contenedores.
- `/docs`: Documentación técnica y diagramas de arquitectura.
- `/tests`: Scripts de pruebas unitarias y automatizadas.

## Requisitos previos
- Docker Desktop
- PostgreSQL 16
- Redis

## Instrucciones de Ejecución Local
1. Clonar el repositorio.
2. Copiar `.env.example` a `.env`.
3. Ejecutar `docker-compose up --build`.
