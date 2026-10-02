# Laboratorio 02 - Criptografía y Seguridad

## Descripción

Laboratorio práctico de ciberseguridad realizado utilizando un entorno controlado con **DVWA (Damn Vulnerable Web Application)**.

El laboratorio aborda el análisis de solicitudes HTTP y ataques de fuerza bruta utilizando diferentes herramientas.

## Herramientas utilizadas

* Docker
* DVWA
* Burp Suite
* cURL
* Hydra
* Wireshark
* Git / GitHub

## Contenidos

### 1. Docker

* Implementación de DVWA mediante Docker.
* Configuración y redirección del puerto `4280`.
* Verificación de los contenedores.

### 2. Burp Suite

* Interceptación de solicitudes HTTP.
* Identificación de parámetros.
* Uso de Intruder.
* Pruebas con diccionarios de usuarios y contraseñas.
* Identificación de credenciales válidas.

### 3. cURL

* Inspección del formulario HTML.
* Reproducción de solicitudes HTTP desde la terminal.
* Comparación entre respuestas válidas e inválidas.
* Identificación de 5 diferencias entre ambas respuestas.

### 4. Hydra

* Verificación de la instalación y versión.
* Ataque automatizado mediante `http-get-form`.
* Uso de listas de usuarios y contraseñas.
* Identificación de combinaciones válidas.

### 5. Wireshark

* Captura del tráfico HTTP mediante la interfaz de loopback.
* Análisis del tráfico generado por cURL.
* Análisis del tráfico generado por Burp Suite.
* Análisis del tráfico generado por Hydra.
* Comparación de los patrones de tráfico.

## Entorno

DVWA fue ejecutado localmente mediante Docker y se accedió utilizando:

```text
http://127.0.0.1:4280
```

El análisis se realizó exclusivamente sobre el entorno de laboratorio local.

## Autor

**José Ignacio Martínez**

Sección: **4**

Octubre 2026
