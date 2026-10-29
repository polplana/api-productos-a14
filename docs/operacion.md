# Operación y resolución de problemas

Guía rápida de administración y resolución de incidencias.

## Iniciar y detener la API
- **Iniciar:** ejecutar `npm start` o `node app.js`.
- **Detener:** pulsar `Ctrl + C` en la terminal donde se ejecuta.

## Comprobar que responde
```bash
curl http://localhost:3000/api/productos
```

## Identificar errores
Revisar los mensajes y la traza de error en la consola donde se ejecuta la aplicación.

## Resolución de problemas
| Problema | Comprobación | Posible solución |
| :--- | :--- | :--- |
| npm no existe | `npm --version` | Instalar Node.js/npm |
| Faltan dependencias | Revisar error al iniciar | Ejecutar `npm install` |
| Puerto 3000 ocupado | Revisar procesos/puertos | Liberar el puerto |
