# GreenTech Backend

Backend desarrollado con Spring Boot utilizando Arquitectura Hexagonal para el proyecto GreenTech.

## Descripción

Este proyecto forma parte del sistema GreenTech, una plataforma orientada al monitoreo ambiental mediante información obtenida desde la API de Copernicus.

El backend implementa una Arquitectura Hexagonal para desacoplar la lógica del negocio de las tecnologías externas.

## Tecnologías

- Java 21
- Spring Boot 3
- Maven
- Arquitectura Hexagonal
- REST API

## Estructura

```
application
domain
infrastructure
```

## Endpoint

GET

```
/api/environment/{region}
```

Ejemplo:

```
/api/environment/amazonas
```

## Historia de Usuario

Como guardabosques,

quiero consultar información ambiental de una región,

para identificar posibles zonas con riesgo de deforestación y tomar decisiones oportunas.

## Autor
Maravi Gamboa Diego Sebastian
Mauricio Hinojoza Luz Mauricio
