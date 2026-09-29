# Sistema Web de Gestión Hospitalaria — Hospital General San Juan

Maquetación en HTML5 y CSS3 (sin backend ni base de datos) del proyecto de
Construye Aplicaciones Web, con base en el mapa de sitio del Producto 1.6 y
el wireframe del Producto 1.8.

## Estructura

```
index.html               Login
panel-paciente.html      Panel Paciente
agendar-cita.html        Agendar Cita (RF-02)
confirmacion-cita.html   Confirmación de Cita (RF-02 y RF-03)
mis-citas.html           Mis Citas (RF-02)
ver-resultados.html      Ver Resultados (RF-04)
notificaciones.html      Centro de Notificaciones (RF-03)
panel-medico.html        Buscar Expediente (RF-05)
historial-clinico.html   Historial Clínico + Alertas de Alergias (RF-05, RNF-04)
panel-admin.html         Panel Administrador
gestion-usuarios.html    Gestión de Usuarios (RF-01)
reportes.html            Reportes Generales (RF-06)
css/estilos.css          Hoja de estilos general (box model, Flexbox/Grid, responsive)
```

Todos los enlaces son internos y funcionan sin backend ni base de datos,
como pide la Lista de Cotejo de Maquetación (criterio 7).

## Probarlo en tu computadora

Abre `index.html` con doble clic, o desde una terminal:

```bash
cd proyecto-hospital
python3 -m http.server 8000
# abre http://localhost:8000 en el navegador
```

## Subirlo a GitHub y publicarlo con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `hospital-general-san-juan`),
   sin README ni .gitignore (para no chocar con estos archivos).
2. En esta carpeta, ejecuta:

```bash
git init
git add .
git commit -m "Maquetación HTML/CSS del Sistema Web de Gestión Hospitalaria"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/hospital-general-san-juan.git
git push -u origin main
```

3. En GitHub, entra al repositorio → **Settings → Pages**.
4. En "Build and deployment", elige **Deploy from a branch**, rama `main`,
   carpeta `/root`, y da clic en **Save**.
5. Espera uno o dos minutos y actualiza la página; GitHub te mostrará el link:
   `https://TU-USUARIO.github.io/hospital-general-san-juan/`
6. Ese es el link que debes generar y entregar.

## Equipo

Ana Gómez, Carlos Pérez, Ezequiel Camacho Reyna, Zoé Domínguez Contreras,
Víctor Iván Lara Padua — Grupo 501.
