# KitCube · Laboratorio de Metrología y MSA

Aplicación educativa interactiva para practicar herramientas estadísticas y estudios de medición.

## Contenido

- Módulo 10: varianza y desviación estándar.
- Módulo 11: fuentes de variación ANOVA.
- Módulo 12: sumas de cuadrados.
- Módulo 13: grados de libertad, cuadrados medios, F y valor p.
- Módulo 14: componentes EV, AV, R&R, PV y TV.
- Módulo 15: indicadores R&R, % contribución, %SV, % tolerancia y ndc.
- Módulos 17–21: caso integrador de medición de diámetro de ejes.

## Uso

Abre `index.html` en un navegador moderno. La aplicación es estática y se adapta a móviles y computadoras. El avance y los intentos se guardan localmente en el navegador del dispositivo.

## Publicación con GitHub Pages

1. En el repositorio, abre **Settings → Pages**.
2. En **Build and deployment → Source**, selecciona **GitHub Actions**.
3. El workflow `.github/workflows/pages.yml` publica automáticamente cada cambio en `main`.

> El progreso de cada alumno se conserva en su propio navegador; esta versión no envía calificaciones a un servidor docente.

## KitCube Academy · acceso de alumnos

La interfaz inicia con una pantalla de acceso de estilo centro de mando. Cada alumno puede:

1. Seleccionar **Crear perfil** y registrar su nombre, matrícula o ID y un PIN de 4 a 12 caracteres.
2. Volver a **Iniciar sesión** usando el mismo ID y PIN.
3. Consultar su rango, XP, insignias, misiones y objetivos secundarios.
4. Cerrar sesión para permitir el acceso de otro alumno en el mismo navegador.

### Alcance del acceso actual

Esta versión es un prototipo de autenticación local para el aula. El perfil, el PIN verificador y el progreso permanecen en el almacenamiento del navegador; el PIN se transforma con SHA-256 antes de guardarse, pero esto **no convierte el sistema en una autenticación de producción**. Los perfiles no se comparten entre dispositivos, navegadores o alumnos que utilicen equipos distintos, y no existe todavía un panel docente ni una base de datos central.

Para habilitar cuentas reales con recuperación de contraseña, sincronización entre dispositivos y seguimiento docente, será necesario conectar un proveedor de autenticación y base de datos (por ejemplo, Supabase o Firebase) y configurar sus credenciales públicas de cliente en el proyecto. No introducir contraseñas importantes ni datos personales sensibles en esta versión local.
