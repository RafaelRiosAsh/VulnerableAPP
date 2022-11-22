# Vulnerable_APP
App insegura basada en estandares OWASP

# Como instalar y correr

### Requerimientos previos

- Crear nuevo repositorio
- Activar venv
- Descargar archivo Wheel

### Instalacion

```pip install flaskr-1.0.0-py3-none-any.whl```

### Inicializar base de datos

```flask --app flaskr init-db```

## iniciar servidor

```flask --app flaskr --debug run```

en caso de necesitar accesar desde otros dispositivos en la misma red usar este comando

```flask --app flaskr --debug run --host 0.0.0.0```
