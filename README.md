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

## KitCube Academy · acceso rápido de alumnos

La pantalla de entrada solicita únicamente el nombre del alumno. No requiere registro, matrícula, correo electrónico ni PIN.

Cada nombre identifica un expediente local: XP, rango, insignias, misiones, intentos y objetivos secundarios se guardan por separado en el navegador utilizado. Al cerrar sesión, puede entrar otro alumno en el mismo equipo escribiendo su nombre.

**Alcance:** el avance permanece en ese navegador y no se sincroniza entre dispositivos. Los alumnos que escriban exactamente el mismo nombre utilizarán el mismo expediente local. Para disponer de cuentas centralizadas, sincronización y panel docente será necesario conectar una base de datos y un servicio de autenticación.
