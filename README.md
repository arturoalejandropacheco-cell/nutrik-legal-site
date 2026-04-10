# Nutrik — Sitio legal y de soporte

Sitio estático con la landing, política de privacidad, términos de servicio y página de soporte de **Nutrik**, la app de seguimiento nutricional con IA para Latinoamérica.

**URL pública:** https://nutrik.driftstudio.tech

## Estructura

```
.
├── index.html      → Landing de Nutrik (hero + features + about)
├── privacy.html    → Política de Privacidad (Ley 19.628 + GDPR + CCPA)
├── terms.html      → Términos de Servicio (incluye descargo médico)
├── support.html    → Centro de ayuda con FAQs
├── CNAME           → Dominio custom para GitHub Pages
└── .nojekyll       → Desactiva Jekyll (procesamiento directo de HTML)
```

## Hosting

Desplegado en **GitHub Pages** con dominio custom `nutrik.driftstudio.tech`.

DNS apuntado desde Donweb:
- Tipo: `CNAME`
- Host: `nutrik`
- Valor: `<tu-usuario-github>.github.io`

## Actualización

Cualquier cambio a estos archivos se publica automáticamente al hacer `git push` a la rama `main`.

## Contacto

Desarrollado por Arturo Pacheco — [Drift Studio](https://driftstudio.tech)
Contacto: admin@driftstudio.tech
