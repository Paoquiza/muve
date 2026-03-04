# Análisis del Sitio Web — muveabogados.com

**Fecha de análisis:** 3 de marzo de 2026
**Sitio evaluado:** [https://muveabogados.com](https://muveabogados.com)
**Tipo de sitio:** Despacho de Abogados
**Plataforma detectada:** Zyro Website Builder (Astro framework)

---

## Scores Generales

| Categoría | Score | Calificación |
|---|---|---|
| **Diseño / Look & Feel** | 4.5 / 10 | Deficiente |
| **SEO (Posicionamiento en Google)** | 3 / 10 | Muy Deficiente |
| **Accesibilidad** | 2.5 / 10 | Crítico |
| **Contenido** | 5 / 10 | Regular |
| **Performance (Velocidad)** | 5 / 10 | Regular |
| **Score Global** | **4 / 10** | **Deficiente** |

---

## 1. Diseño / Look & Feel — 4.5/10

### Deficiencias encontradas

- **Inconsistencia de marca:** El header muestra "MUÑOZ & VENTRÉ ABOGADOS" pero el dominio y branding es "Muve Abogados". Esto genera confusión de identidad.
- **Paleta de colores inadecuada para el sector:** El morado primario (#673de6) es poco convencional para un despacho de abogados. Los colores no transmiten seriedad, confianza ni profesionalismo jurídico (se esperan azules oscuros, grises, dorados).
- **Jerarquía visual rota:** Se usan H3 y H6 de forma arbitraria sin H2. Saltar de H1 directamente a H3 rompe la estructura visual y semántica.
- **Widget de WhatsApp genérico:** Burbuja flotante que se siente como template, no personalizada.
- **Sitio construido con Zyro (website builder):** Se nota la limitación del builder en la calidad del diseño. Las imágenes se sirven desde `assets.zyrosite.com`, lo cual es poco profesional para un despacho legal.
- **Footer genérico:** "© 2025 Powered by Belle Marketing Agency" — muestra que es un sitio de template, restando credibilidad.
- **Tipografía:** No se detectan fuentes profesionales cargadas explícitamente; probablemente usa las del sistema o las por defecto del builder.

---

## 2. SEO (Posicionamiento en Google) — 3/10

### Deficiencias críticas

- **Sin etiqueta canonical:** No hay `<link rel="canonical">`, lo que puede causar problemas de contenido duplicado.
- **Sin Open Graph tags:** No hay meta tags para Facebook, Twitter Cards, ni redes sociales. Los links compartidos se verán genéricos.
- **Sin viewport meta tag visible:** Crítico para indexación mobile-first de Google.
- **Keywords meta tag obsoleto:** Usan `keywords: "abogados, asesoría legal, conflictos legales"` — Google ignora esta etiqueta desde 2009.
- **Solo 4 páginas en el sitemap:** Un sitio de abogados debería tener páginas individuales por área de práctica, blog jurídico, FAQ, etc.
- **Sin blog ni contenido dinámico:** No hay estrategia de content marketing. Cero artículos, cero páginas de práctica detalladas.
- **Schema markup mínimo:** Solo tiene `WebSite` schema. Falta `LegalService`, `Attorney`, `LocalBusiness`, `FAQPage`.
- **Sin hreflang específico:** No hay `<html lang="es-MX">` para México.
- **Meta description genérica:** No está optimizada con keywords de alto valor ni incluye ubicación geográfica.
- **Sin Google Business Profile linkado:** No hay evidencia de conexión con Google Maps/Business.
- **URLs sin optimizar:** Solo 4 páginas con slugs básicos (`/servicios`, `/equipo`, `/contacto`).

---

## 3. Accesibilidad — 2.5/10

### Deficiencias críticas

- **Cero alt text en imágenes:** Ninguna imagen tiene texto alternativo. Violación directa de WCAG 2.1 AA.
- **Sin ARIA labels:** No se detectan atributos `aria-*` en elementos interactivos.
- **Sin skip navigation:** No hay enlace para saltar al contenido principal.
- **Formulario sin labels asociados:** El campo de email no tiene `<label>` vinculado.
- **Contraste de colores dudoso:** El morado sobre blanco puede no cumplir ratio 4.5:1.
- **Navegación duplicada:** Estructura de nav duplicada para mobile/desktop en lugar de usar CSS responsive.

---

## 4. Contenido — 5/10

### Fortalezas

- Propuesta de valor clara ("Hacemos la diferencia").
- Testimonios de clientes con calificación 5 estrellas.
- Tres áreas de servicio definidas (Asesoría, Consultoría, Representación).

### Deficiencias

- **Contenido superficial:** Las descripciones de servicios son genéricas, no específicas del despacho.
- **Sin páginas individuales por práctica:** No hay páginas dedicadas para derecho corporativo, penal, civil, etc.
- **Sin FAQ:** Oportunidad perdida para SEO y confianza del usuario.
- **Estadísticas vagas:** "200+ clientes satisfechos", "150+ confianza total" — la segunda no tiene sentido como métrica.
- **Sin casos de éxito detallados:** Solo testimonios cortos, no case studies.
- **Sin información del equipo en homepage:** La página de equipo existe pero no se promociona.

---

## 5. Performance / Técnico — 5/10

### Deficiencias

- **Hosting en Zyro/builder:** Limitaciones inherentes de performance y personalización.
- **Imágenes desde CDN externo:** `assets.zyrosite.com` agrega latencia y dependencia de terceros.
- **JavaScript de hidratación Astro:** Overhead innecesario para un sitio mayormente estático.
- **Sin lazy loading evidente:** Las imágenes probablemente cargan todas al inicio.
- **Copyright 2025 desactualizado:** Estamos en 2026, denota abandono.

---

## 6. Recomendaciones Prioritarias

### Urgente (Impacto Alto)

1. Migrar a un CMS profesional (WordPress + tema legal, o sitio custom con Next.js/Astro propio).
2. Agregar alt text a TODAS las imágenes.
3. Implementar Open Graph, canonical tags y viewport meta.
4. Crear páginas individuales por área de práctica legal.
5. Agregar Schema markup `LegalService` y `LocalBusiness`.

### Importante (Impacto Medio)

6. Rediseñar paleta de colores (azules/grises profesionales).
7. Unificar identidad de marca (resolver "Muve" vs "Muñoz & Ventré").
8. Iniciar blog jurídico con contenido SEO.
9. Agregar página de FAQ con schema `FAQPage`.
10. Vincular Google Business Profile.

### Deseable (Impacto Menor)

11. Mejorar formulario de contacto con más campos.
12. Agregar mapa de ubicación.
13. Implementar analytics (GA4).
14. Agregar testimonios en Google Reviews.
15. Optimizar Core Web Vitals.

---

## Veredicto Final

El sitio actual funciona como una **tarjeta de presentación digital básica**, pero **no como una herramienta de captación de clientes** ni de posicionamiento en buscadores. Para un despacho de abogados, la credibilidad visual y el SEO local son fundamentales, y ambos son muy débiles en este sitio.

> Un rediseño completo con enfoque en SEO local, contenido de valor y diseño profesional podría incrementar la captación de clientes potenciales de forma significativa.
