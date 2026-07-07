# SAGA Group Foundation — Sitio web

Sitio institucional estático de la **Fundación Grupo Sinergia para la Aceleración y Gestión de las Artes (SAGA)**.
`sagagroup.org` · Manizales, Eje Cafetero.

## Estructura

```
index.html          Página única (institucional)
logo.png            Logo azul (header) — 1080×384
logo-blanco.png     Logo blanco/línea roja (footer, fondos oscuros)
img/                Fotos de eventos culturales (rescatadas del sitio anterior)
netlify.toml        Configuración de despliegue (sin build)
```

## Identidad visual

- Azul marino `#15204d` · Coral `#e07a5f` · Blanco cálido `#f6f3ee`.

## Desplegar en Netlify (desde GitHub)

1. Crear un repo en GitHub y subir el **contenido de esta carpeta** a la raíz del repo.
2. En Netlify: **Add new site → Import from GitHub** → elegir el repo.
3. Build command: *(vacío)* · Publish directory: `.` (ya definido en `netlify.toml`).
4. Deploy. Netlify da una URL `*.netlify.app`.
5. Conectar dominio `sagagroup.org`: **Domain settings → Add custom domain** y **repuntar el DNS** desde HostGator hacia Netlify (los registros que indique Netlify).

> Cada `git push` a la rama principal redespliega automáticamente.

## Enlaces reales usados en el sitio

- Donación (Vaki): https://vaki.co/sinergiaparalasartesylacultura
- Instagram: https://www.instagram.com/fundacionsagagroup/
- Facebook: https://www.facebook.com/profile.php?id=100086299201305
- Correo: gruposaga2022@gmail.com
