# Calculadora CI

## Descripción

Este proyecto es una calculadora básica en PHP desarrollada para el taller de Desarrollo de Software II. Incluye operaciones aritméticas fundamentales y pruebas unitarias con PHPUnit.

## Características

- Suma, resta, multiplicación y división.
- Pruebas unitarias en `tests/CalculadoraTest.php`.
- Integración con GitHub Actions para ejecutar pruebas automáticamente.

## Estructura del proyecto

- `src/Calculadora.php` — lógica de la calculadora.
- `tests/CalculadoraTest.php` — casos de prueba para validar las operaciones.
- `composer.json` — configuración de autoload y dependencias.
- `.github/workflows/php-ci.yml` — pipeline de CI para ejecutar PHPUnit.

## Requisitos

- PHP 8.2 o superior
- Composer

## Instalación

Desde la raíz del proyecto, ejecuta:

```sh
composer install
```

## Ejecutar pruebas

```sh
vendor/bin/phpunit tests
```

## GitHub Actions

Este repositorio está preparado para ejecutar pruebas automáticas en cada push y pull request. El workflow ubicado en `.github/workflows/php-ci.yml` realiza:

1. Checkout del código.
2. Instalación de PHP 8.2.
3. Instalación de dependencias de y con Composer.
4. Ejecución de `vendor/bin/phpunit tests`.

## Badge de estado

![PHP CI](https://github.com/<usuario>/<repo>/actions/workflows/php-ci.yml/badge.svg)

> Reemplaza `<brayanjairsinisterra-tech>` y `<https://github.com/brayanjairsinisterra-tech/parcial2.git>` por el usuario y repositorio reales para que el badge funcione.

## Uso

Puedes usar la calculadora directamente importando la clase `App\Calculadora` desde `src/Calculadora.php` y llamando a sus métodos para cada operación.

## Integrantes

- BRAYAN JAIR SINISTERRA


## Notas de entrega

- Agrega el badge de GitHub Actions verdadero.
- Coloca la URL pública de tu repositorio.
- Incluye los nombres completos de los integrantes.
- Procura tener al menos 3-4 commits con mensajes claros.
