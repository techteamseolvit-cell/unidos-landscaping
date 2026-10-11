# Pendientes del sitio web (según el X-Ray) - revisado en vivo el 2026-10-11

Leyenda: **TÚ** = lo haces en WordPress / lo decide el cliente. **YO** = lo preparo (JSON, textos, fichas). **AMBOS** = yo preparo, tú cargas.

## Páginas existentes
### Home `/`  (la más avanzada)
- [ ] TÚ/YO: texto alternativo en 9 imágenes (me pasas los nombres de archivo y te doy los textos).
- [ ] TÚ: validar con el cliente las 6 respuestas de la FAQ (las redacté yo, sin precios ni números).
- [ ] AMBOS: sección de before/after como mini casos de estudio (ubicación, tipo de trabajo, materiales). Necesito proyectos y datos reales.
- [ ] AMBOS: datos estructurados LocalBusiness (teléfono, área de servicio) con Yoast o un bloque.

### Services `/services/`
- [ ] YO: H1 "Our Services" -> "Landscaping Services in Albuquerque, NM" + línea "Proudly serving Albuquerque, Rio Rancho and Corrales" (necesito el JSON actual).
- [ ] TÚ: crear la página Landscaping & Maintenance y enlazar el primer bloque (hoy sin enlace).
- [ ] TÚ/YO: texto alternativo en 8 imágenes.

### Residential Landscaping `/residential-landscaping/`
- [ ] YO: H1 con Albuquerque ("Residential Landscaping in Albuquerque, NM") + "Proudly serving..."
- [ ] YO: botón "GET A QUOTES" -> "Get a Free Estimate"; "Others Services" -> "Other Services".
- [ ] YO: cambiar el formulario por el de LeadConnector.
- [ ] YO: enlazar los servicios de la lista a sus landing pages. (Decisión: ¿se pasa a borrador o se mantiene?)
- [ ] TÚ/YO: alt en 1 imagen.

### Commercial Landscaping `/commercial-landscaping/`
- [ ] YO: H1 con Albuquerque + "Proudly serving..."; botón "GET A QUOTES" -> "Get a Free Estimate"; formulario LeadConnector; enlaces a landing pages.
- [ ] Decisión: ¿borrador o se mantiene?

### Why Choose Us `/why-choose-us/`
- [ ] YO: H1 "Why Choose Unidos Landscaping in Albuquerque, NM".
- [ ] YO: agregar las reseñas de Google ([trustindex no-registration=google]) como prueba social.
- [ ] TÚ/YO: alt en 5 imágenes.

### Contact Us `/contact-us/`
- [ ] YO: H1 "Get a Free Landscaping Estimate in Albuquerque, NM".
- [ ] TÚ: corregir el mapa: la dirección dice "Alburquerque, Rio rancho, Corrales" -> "Albuquerque, Rio Rancho, Corrales".

## Landing pages de servicio
Pendiente en las 8 publicadas:
- [ ] YO/AMBOS: línea "Proudly serving Albuquerque, Rio Rancho and Corrales" en el banner (la quitó la plantilla).
- [ ] TÚ: subir las 3 imágenes por página (banner + 2) con alt (ver image-prompts.md).
- [ ] TÚ: 1 imagen sin alt por página.

| Página | Estado | Pendiente específico |
|---|---|---|
| Landscaping & Maintenance | **NO publicada (404)** | Crear la página con el JSON, ficha Yoast, enlazar desde Services. |
| Irrigation `/irrigation-repair-albuquerque/` | Publicada | Solo lo común. |
| Service Calls `/landscaping-service-calls-albuquerque/` | Publicada | Title Yoast: hoy "landscaping service calls Albuquerque \| Unidos Landscaping" -> "Service Calls Albuquerque, NM \| Unidos Landscaping". |
| Outdoor Lighting | Publicada | Solo lo común. |
| Xeriscaping | Publicada | **Prioridad SEO del X-Ray:** proyectos reales de ABQ, ahorro de agua, plantas nativas. Faltan fotos/datos reales. |
| Seasonal Cleanups `/yard-cleanup-albuquerque/` | Publicada | Title Yoast dice "Yard Cleanup" -> "Seasonal Cleanups Albuquerque, NM \| Unidos Landscaping"; keyphrase "seasonal cleanups Albuquerque"; valorar slug `seasonal-cleanups-albuquerque` con redirección 301. |
| Masonry | Publicada | Solo lo común. |
| Concrete | Publicada | Solo lo común. |
| Pavers | Publicada | Solo lo común. |

## Generales
- [ ] TÚ: enviar `/sitemap_index.xml` a Google Search Console.
- [ ] TÚ: testimonios: pedir reseña de Google a cada cliente al entregar el proyecto (sistema de recolección).
- [ ] TÚ: medir envíos del formulario de LeadConnector si se usarán las landing pages como destino de anuncios.
- [ ] Revisar con el cliente: textos de garantía y "Materials & Warranties" (genéricos).

## Decisiones tomadas (fuera del alcance actual)
- Páginas de Rio Rancho y Corrales (fase 3 del X-Ray): no se harán; solo las 9 landing pages.
- Página de Sod Installation: no se hará; queda como línea en Residential.
