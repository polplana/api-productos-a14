# Procedimiento de despliegue

Pasos reales para poner la API en funcionamiento en un entorno de despliegue.

## Pasos de despliegue
1. Clonar el repositorio en el servidor:
```bash
git clone  https://github.com/polplana/api-productos-a14.git
cd api-productos-a14
```

2. Instalar dependencias:
```bash
npm install
```

3. Iniciar la aplicación:
```bash
npm start
```

4. Comprobar que responde:
```bash
curl http://localhost:3000/api/productos
```
## Checklist básico
- [ ] No se han incluido contraseñas ni secretos en el repositorio
- [ ] Los posibles ficheros con secretos están incluidos en .gitignore
- [ ] En producción debería utilizarse HTTPS
- [ ] Solo deberían exponerse los puertos necesarios