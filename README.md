# El Diagnóstico · Taller ILC

Simulador de diagnóstico y rutas de inspección para entrenamiento de confiabilidad — Ingenio La Cabaña.

## Desarrollo local

```bash
python -m http.server 8765
```

Abrí `http://localhost:8765/` en el navegador.

## Despliegue en Vercel

Sitio estático: no requiere build ni install. Vercel sirve `index.html` en la raíz.

**Importante:** en Vercel → Project Settings → Build & Development Settings, usá el preset **Other** (sin framework).
