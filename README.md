# barberiaOFICIAL

Sistema de Información para gestionar agenda, flujo de caja, inventario y comisiones - UAGRM FICCT.

## Configuración inicial (para el equipo)

1. Clonar el repositorio:

   git clone https://github.com/jherargm412-dev/barberiaOFICIAL.git

2. Crear la base de datos en PostgreSQL local:

   CREATE DATABASE barberia;

3. Configurar credenciales:
   - Ir a la carpeta backend/src/main/resources/
   - Copiar el archivo application.properties.example y renombrar la copia a application.properties
   - Poner tu usuario y contraseña de PostgreSQL en ese archivo

4. Ejecutar el proyecto desde BackendApplication.java
   (Las tablas se crean automáticamente al iniciar gracias a Hibernate)

## Reglas del equipo

- Nadie hace push directo a main
- Cada quien trabaja en su propia rama
- Los cambios se integran por Pull Request revisado por al menos un compañero