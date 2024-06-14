# API REST de E-commerce en Go

## Instalación

Hay algunas herramientas que necesitas instalar para ejecutar el proyecto.
Así que asegúrate de tener las siguientes herramientas instaladas en tu máquina.

- [Migrate (para migraciones de BD)](https://github.com/golang-migrate/migrate/tree/v4.17.0/cmd/migrate)

## Ejecutando el proyecto

Primero asegúrate de tener una base de datos MySQL funcionando en tu máquina o simplemente cambia a cualquier almacenamiento que prefieras en `/db`.

Luego crea una base de datos con el nombre que desees *(el nombre predeterminado es `APIdb`)* y ejecuta las migraciones.

```bash
make migrate-up
```

Después de eso, puedes ejecutar el proyecto con el siguiente comando:

```bash
make run
```

## Ejecutando las pruebas

Para ejecutar las pruebas, puedes usar el siguiente comando:

```bash
make test
```
