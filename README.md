# Calculadora CI

## Descripción

Proyecto del taller de Desarrollo de Software II. Esta calculadora en PHP incluye:

- `src/Calculadora.php`: operaciones básicas de suma, resta, multiplicación y división.
- `tests/CalculadoraTest.php`: pruebas unitarias con PHPUnit.
- `.github/workflows/php-ci.yml`: pipeline de GitHub Actions para ejecutar pruebas automáticamente.

## Getting Started

### Requisitos

- PHP 8.2
- Composer

### Instalación

Desde la raíz del proyecto:

```sh
composer install
```

### Ejecutar pruebas

```shn
vendor/bin/phpunit tests
```

## GitHub Actions

El workflow se encuentra en `.github/workflows/php-ci.yml` y realiza:

1. checkout del repositorio
2. instalación de PHP 8.2 con `shivammathur/setup-php`
3. instalación de dependencias con Composer
4. ejecución de `./vendor/bin/phpunit tests`


## Badge de estado

![PHP CI](https://github.com/<usuario>/<repo>/actions/workflows/php-ci.yml/badge.svg)

## Repositorio público

https://github.com/<usuario>/<repo>

## Entrega

- Agrega al README el badge de GitHub Actions funcionando.
- Agrega al README la URL pública de tu repositorio.
- Agrega los nombres completos de los integrantes.
- Asegúrate de tener al menos 3-4 commits con mensajes claros.

## Integrantes

- Nombre completo 1
- Nombre completo 2

> Reemplaza `<usuario>` y `<repo>` con tu cuenta y repositorio reales, y agrega tus nombres completos.
