# Nutrika — Sitio legal y de soporte

Sitio estático con la landing, política de privacidad, términos de servicio y página de soporte de **Nutrika**, la app de seguimiento nutricional con IA para Latinoamérica.

**URL pública:** https://nutrik.driftstudio.tech

Disponible en **español** (raíz del sitio) y en **inglés** (carpeta [`/en/`](en/)), con un enlace para cambiar de idioma en cada página.

## Estructura

```
.
├── index.html          → Landing de Nutrika (hero + features + about)
├── privacy.html        → Política de Privacidad (Ley 19.628 + GDPR + CCPA)
├── terms.html          → Términos de Servicio (incluye descargo médico)
├── support.html        → Centro de ayuda con FAQs
├── delete-account.html → Cómo eliminar la cuenta y los datos
├── en/                 → Versión en inglés de las 5 páginas anteriores
│   ├── index.html
│   ├── privacy.html
│   ├── terms.html
│   ├── support.html
│   └── delete-account.html
├── CNAME                → Dominio custom para GitHub Pages
└── .nojekyll             → Desactiva Jekyll (procesamiento directo de HTML)
```

## Hosting

Desplegado en **GitHub Pages** con dominio custom `nutrik.driftstudio.tech`.

DNS apuntado desde Donweb:
- Tipo: `CNAME`
- Host: `nutrik`
- Valor: `<tu-usuario-github>.github.io`

## Actualización

Cualquier cambio a estos archivos se publica automáticamente al hacer `git push` a la rama `main`.

Al editar contenido legal o de marca, actualiza **ambos idiomas** (la página en español y su
equivalente en `/en/`) para que no queden desincronizados.

## Contacto

Desarrollado por Arturo Pacheco — [Drift Studio](https://driftstudio.tech)
Contacto: admin@driftstudio.tech
