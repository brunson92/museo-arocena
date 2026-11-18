# PRD: Landing Page "Planes y Experiencias Museo Arocena"

| Campo | Detalle |
|---|---|
| **Producto** | Landing page de paquetes, alianzas y planeador de visita |
| **Organización** | Museo Arocena, Torreón, Coahuila |
| **Versión** | 0.1 (borrador) |
| **Fecha** | 17 de noviembre de 2026 |
| **Estado** | Propuesta para validación con la dirección del museo |

> **Nota:** los datos del museo (horarios, costos, aforos, espacios) están marcados como `[POR VALIDAR]` y deben confirmarse con el museo antes del diseño final.

---

## 1. Resumen ejecutivo

El Museo Arocena cuenta con acervo, espacios y programación que hoy no se comunican ni se consumen como una **experiencia completa**. Esta propuesta convierte esos recursos en **paquetes de planes temáticos** para distintos públicos, apoyados en **alianzas comerciales** con empresas locales (gastronomía, hospedaje, transporte, comercios, etc.), y en una **herramienta digital** para consultar la oferta, conocer eventos y planear la visita.

La **landing page** es la puerta de entrada de esta propuesta: presenta la oferta, explica el valor para visitantes y aliados, y lleva a la acción (planear visita, reservar o solicitar información).

## 2. Contexto y problema

### Problema
- Los visitantes potenciales no tienen un lugar único donde ver **qué hacer, cuándo y cómo planear** su visita.
- La oferta del museo se percibe como una visita puntual, no como parte de un **plan de día o fin de semana**.
- Las empresas locales no tienen un canal claro para **aliarse** con el museo y beneficiarse de su público.
- El museo aprovecha poco sus recursos existentes (espacios, jardines, auditorio, tienda, salas temporales, etc.) `[POR VALIDAR]`.

### Oportunidad
- Aumentar visitas y recurrencia sin grandes inversiones, reutilizando recursos existentes.
- Generar nuevas fuentes de ingreso (paquetes, patrocinios, eventos privados).
- Posicionar al museo como **punto de referencia cultural y turístico** de la Comarca Lagunera.

## 3. Objetivos y métricas de éxito

### Objetivos
1. Dar a conocer la oferta de paquetes y experiencias temáticas.
2. Facilitar la planeación de una visita (qué ver, cuándo, con quién, qué más hacer cerca).
3. Captar **empresas aliadas** y prospectos de patrocinio.
4. Generar una base de contactos (visitantes y aliados) para comunicación futura.

### KPIs (a 90 días del lanzamiento, valores objetivo por calibrar)

| Métrica | Objetivo sugerido |
|---|---|
| Visitas únicas a la landing | Línea base + crecimiento mensual `[definir]` |
| Tasa de conversión a acción principal (planear/reservar) | 5 a 8 % |
| Clics en "Ver paquetes" | 35 % de los visitantes |
| Solicitudes de alianza comercial | 10 a 15 empresas contactadas |
| Suscripciones al boletín / WhatsApp | 300+ |
| Tráfico móvil con buena experiencia (LCP < 2.5 s) | 90 % |

## 4. Usuarios objetivo

| Persona | Necesidad | Qué busca en la landing |
|---|---|---|
| **Familias con niños** | Plan de fin de semana económico y seguro | Paquete familiar, horarios, talleres, comida cercana |
| **Escuelas y docentes** | Visitas educativas organizadas | Paquete escolar, costos grupales, solicitud de visita |
| **Parejas y jóvenes adultos** | Plan cultural diferente | Noches de museo, cena + visita, eventos especiales |
| **Turistas y visitantes foráneos** | Armar un día completo en Torreón | Ruta cultural, hospedaje, transporte, qué más visitar |
| **Adultos mayores** | Visitas tranquilas y accesibles | Recorridos guiados, accesibilidad, horarios cómodos |
| **Empresas** | Convivencia, eventos o imagen de marca | Eventos corporativos, renta de espacios, patrocinio |
| **Empresas aliadas potenciales** | Visibilidad y nuevos clientes | Beneficios de ser aliado, cómo sumarse |

## 5. Propuesta de valor

- **Para visitantes:** "Planea tu día en el Museo Arocena en minutos: arte, historia, comida y más, todo en un solo plan."
- **Para aliados:** "Conecta tu marca con un público cultural y local, con presencia en los paquetes y canales del museo."
- **Para el museo:** Más visitantes, mayor recurrencia y nuevas fuentes de ingreso con los recursos que ya tiene.

## 6. Alcance

### Dentro del alcance (MVP)
- Landing page responsiva de una sola página con secciones ancladas.
- Catálogo visual de paquetes por tipo de público.
- Calendario / listado de eventos y actividades especiales.
- Sección para empresas aliadas (actuales y cómo sumarse) con formulario.
- Planeador de visita **básico** (selección de perfil, fecha y plan sugerido).
- Formularios de contacto, reserva por WhatsApp/correo y suscripción.
- Analítica y SEO básico.

### Fuera del alcance (fases posteriores)
- Pasarela de pago y venta de boletos en línea.
- App móvil nativa.
- Cuentas de usuario y programa de lealtad.
- Panel de administración avanzado para aliados.
- Integración con sistemas de taquilla o CRM `[evaluar en fase 2]`.

## 7. Estructura de la landing (arquitectura de información)

1. **Header / navegación fija:** logo, secciones, botón principal "Planea tu visita".
2. **Hero**
3. **¿Por qué visitar el Museo Arocena?** (3 a 4 diferenciadores)
4. **Paquetes y experiencias por público**
5. **Actividades y eventos especiales**
6. **Planeador de visita**
7. **Aliados del museo**
8. **Súmate como aliado**
9. **Información práctica** (horarios, costos, ubicación, accesibilidad)
10. **Testimonios / galería** (cuando existan)
11. **Preguntas frecuentes**
12. **CTA final + suscripción**
13. **Footer** (contacto, redes, aviso de privacidad)

## 8. Requerimientos funcionales por sección

### 8.1 Hero
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-01 | Titular claro, subtítulo y fotografía/video representativo del museo | Must |
| F-02 | CTA primario: "Planea tu visita" (ancla al planeador) | Must |
| F-03 | CTA secundario: "Ver paquetes" | Must |
| F-04 | Datos rápidos visibles: horario de hoy y ubicación `[POR VALIDAR]` | Should |

**Copy sugerido:**
- Titular: *"Vive el Museo Arocena como nunca: arte, historia y experiencias para todos"*
- Subtítulo: *"Elige tu plan, suma comida, actividades y más. Nosotros te ayudamos a armarlo."*

### 8.2 Paquetes y experiencias por público
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-05 | Tarjetas de paquetes con nombre, público, qué incluye, duración, precio/rango y aliados incluidos | Must |
| F-06 | Filtro por tipo de público (familia, escuela, pareja, turista, adulto mayor, empresa) | Must |
| F-07 | Botón por paquete: "Reservar / Solicitar" (WhatsApp o formulario) | Must |
| F-08 | Detalle expandible (modal o página interna) con itinerario del plan | Should |
| F-09 | Etiquetas de temporada o edición limitada | Could |

**Ejemplos de paquetes (borrador, sujetos a validación):**

| Paquete | Público | Incluye (ejemplo) | Posibles aliados |
|---|---|---|---|
| **Domingo en familia** | Familias | Entrada + recorrido lúdico + taller infantil + descuento en comida | Restaurante / cafetería local |
| **Aprende en el Arocena** | Escuelas | Visita guiada educativa + material didáctico + opción de transporte | Empresa de transporte escolar |
| **Noche de museo** | Parejas / jóvenes | Recorrido nocturno + copa o café + descuento en cena | Restaurante, café, cervecería local |
| **Torreón cultural en un día** | Turistas | Museo + ruta sugerida + comida + transporte | Hoteles, agencias, transporte |
| **Recorrido sin prisa** | Adultos mayores | Recorrido guiado de ritmo tranquilo + refrigerio | Cafetería, transporte accesible |
| **Evento corporativo** | Empresas | Renta de espacio + visita guiada + banquete | Catering, proveedores de eventos |

### 8.3 Actividades y eventos especiales
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-10 | Lista o calendario de próximos eventos con fecha, hora, costo y descripción | Must |
| F-11 | Filtros por fecha y tipo de actividad (taller, recorrido, evento de temporada) | Should |
| F-12 | Botón "Agregar a mi calendario" (archivo .ics / Google Calendar) | Could |
| F-13 | Actualización de eventos sin intervención técnica (hoja de cálculo o CMS ligero) | Must |

### 8.4 Planeador de visita
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-14 | Flujo guiado de 3 a 4 pasos: ¿con quién vienes?, ¿qué día?, ¿cuánto tiempo tienes?, ¿qué más te interesa? | Must |
| F-15 | Resultado: plan sugerido (paquete recomendado, eventos de esa fecha, aliados cercanos) | Must |
| F-16 | Compartir o guardar el plan (enlace, WhatsApp, PDF o captura) | Should |
| F-17 | Capturar correo o WhatsApp opcional para enviar el plan | Should |
| F-18 | Mapa con museo y aliados cercanos | Could |

### 8.5 Aliados del museo
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-19 | Carrusel o cuadrícula de logos de aliados con descripción del beneficio | Must |
| F-20 | Ficha por aliado: qué ofrece, descuento/promoción y ubicación | Should |
| F-21 | Aviso claro de cómo canjear beneficios (boleto, código, pulsera, etc.) `[definir mecánica]` | Should |

### 8.6 Súmate como aliado
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-22 | Explicación de beneficios para la empresa (visibilidad, paquetes, difusión, público cultural) | Must |
| F-23 | Niveles o tipos de alianza (descuento, patrocinio de evento, paquete conjunto, patrocinio anual) | Should |
| F-24 | Formulario: empresa, giro, contacto, tipo de alianza de interés, mensaje | Must |
| F-25 | Descarga de dossier / presentación para aliados (PDF) | Should |

### 8.7 Información práctica y FAQ
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-26 | Horarios, costos, dirección, mapa, estacionamiento, accesibilidad `[POR VALIDAR]` | Must |
| F-27 | Preguntas frecuentes en acordeón (reservas, grupos, cancelaciones, fotografía, mascotas, etc.) | Should |
| F-28 | Botón flotante de WhatsApp | Should |

### 8.8 Captación y cierre
| ID | Requerimiento | Prioridad |
|---|---|---|
| F-29 | Suscripción a boletín o lista de difusión con consentimiento explícito | Must |
| F-30 | Aviso de privacidad accesible y casilla de aceptación en formularios | Must |

## 9. Requerimientos no funcionales

| Categoría | Requerimiento |
|---|---|
| **Rendimiento** | LCP < 2.5 s en 4G; imágenes optimizadas (WebP/AVIF) y carga diferida |
| **Responsividad** | Mobile-first; la mayoría del tráfico esperado es desde celular |
| **Accesibilidad** | Cumplimiento WCAG 2.1 AA: contraste, navegación por teclado, texto alternativo, tamaños legibles |
| **SEO** | Metaetiquetas, datos estructurados (Museum, Event), URLs limpias, sitemap; términos como "museo en Torreón", "qué hacer en Torreón" |
| **Seguridad y privacidad** | HTTPS, protección contra spam en formularios, cumplimiento de la LFPDPPP (México) |
| **Analítica** | GA4 o similar + eventos personalizados (ver sección 10) |
| **Mantenibilidad** | Contenido editable por el personal del museo sin programar |
| **Idioma** | Español (MX) en el MVP; inglés como mejora futura para turismo |
| **Compatibilidad** | Últimas 2 versiones de Chrome, Safari, Edge y Firefox; iOS y Android |

## 10. Analítica y eventos a medir

- `click_planear_visita`, `click_ver_paquetes`
- `filtro_publico_seleccionado`
- `paquete_solicitado` (con nombre del paquete)
- `planeador_iniciado`, `planeador_completado`
- `evento_agregado_calendario`
- `formulario_aliado_enviado`
- `click_whatsapp`
- `suscripcion_completada`
- Embudo: visita → ver paquetes → solicitar → confirmación

## 11. Diseño y contenido

### Lineamientos de diseño
- Respetar la identidad visual del Museo Arocena `[solicitar manual de marca / logotipo]`.
- Fotografía real del museo, colecciones y visitantes (con autorización de uso).
- Estética cultural, cálida y limpia; mucho aire en blanco, tipografía legible.
- Llamadas a la acción consistentes y de alto contraste.
- Iconografía simple para cada tipo de público.

### Tono de comunicación
Cercano, invitador y claro; evitar tecnicismos museográficos. Dirigirse al visitante de "tú".

### Contenido que debe proporcionar el museo
- Logotipo, paleta y tipografías
- Fotografías y videos en alta calidad
- Horarios, tarifas, políticas de grupos y accesibilidad
- Calendario de actividades y descripción de talleres/recorridos
- Lista de aliados actuales y condiciones de beneficios
- Textos legales: aviso de privacidad y términos

## 12. Flujos clave de usuario

**Flujo A: Familia que quiere planear un domingo**
Llega desde redes o buscador → ve hero → filtra "Familias" → revisa paquete "Domingo en familia" → pulsa "Reservar" → mensaje de WhatsApp prellenado.

**Flujo B: Turista que arma su día**
Entra al planeador → selecciona "turista", fecha y 4 horas → recibe plan con museo + comida + evento del día → comparte por WhatsApp o guarda el plan.

**Flujo C: Empresa que quiere aliarse**
Ve la sección "Súmate" → descarga dossier → llena formulario → el museo recibe notificación por correo.

## 13. Dependencias y supuestos

- El museo aprueba la oferta de paquetes y precios.
- Existen o se firmarán acuerdos con al menos 3 a 5 aliados para el lanzamiento.
- El museo designa a una persona responsable de contenido y de atender solicitudes.
- Existe un canal de atención (WhatsApp Business o correo) para reservas.
- En el MVP las reservas se confirman manualmente (sin pago en línea).

## 14. Riesgos y mitigaciones

| Riesgo | Impacto | Mitigación |
|---|---|---|
| Pocos aliados al lanzamiento | Oferta limitada | Lanzar con paquetes propios del museo y sumar aliados por etapas |
| Información desactualizada (eventos, horarios) | Pérdida de confianza | Contenido editable fácil + responsable asignado + revisión semanal |
| Solicitudes sin respuesta oportuna | Mala experiencia | Definir SLA de respuesta (ej. 24 h) y plantillas |
| Bajo tráfico | Poca conversión | Plan de difusión: redes, escuelas, cámaras empresariales, turismo local |
| Complejidad del planeador | Retraso | MVP con lógica simple por reglas; evolucionar después |
| Mecánica de canje poco clara | Frustración de usuarios y aliados | Definir un método único y sencillo (código o boleto) antes del lanzamiento |

## 15. Plan de implementación (propuesta)

| Fase | Duración estimada | Entregables |
|---|---|---|
| **0. Descubrimiento** | 1 a 2 semanas | Validación de oferta, datos del museo, primeros aliados, manual de marca |
| **1. Diseño** | 2 semanas | Wireframes, diseño visual, copy, aprobación |
| **2. Desarrollo MVP** | 3 a 4 semanas | Landing, formularios, catálogo, eventos, planeador básico, analítica |
| **3. Pruebas y ajustes** | 1 semana | QA, accesibilidad, rendimiento, pruebas con usuarios reales |
| **4. Lanzamiento** | 1 semana | Publicación, campaña de difusión inicial |
| **5. Iteración** | Continuo | Medición, mejoras, venta en línea y panel de aliados |

## 16. Criterios de aceptación del MVP

- [ ] La landing carga correctamente en móvil y escritorio y cumple los umbrales de rendimiento.
- [ ] Se muestran al menos 4 paquetes con filtro por público.
- [ ] El calendario de eventos puede actualizarse sin ayuda de un desarrollador.
- [ ] El planeador entrega un plan sugerido en máximo 4 pasos.
- [ ] Los formularios envían notificación al museo y confirmación al usuario.
- [ ] Hay al menos 3 aliados visibles con beneficio claramente descrito.
- [ ] Aviso de privacidad y consentimiento implementados.
- [ ] Analítica registra todos los eventos definidos en la sección 10.
- [ ] Revisión de accesibilidad básica aprobada.

## 17. Preguntas abiertas

1. ¿Cuáles son los horarios, tarifas y aforos actuales del museo?
2. ¿Qué espacios y recursos pueden ofrecerse en paquetes (auditorio, jardines, salas temporales, tienda, cafetería)?
3. ¿Qué aliados ya existen o están dispuestos a sumarse de inmediato?
4. ¿Cómo se canjearán los beneficios de los aliados (código, boleto, pulsera, QR)?
5. ¿Se cobrará algo a los aliados o será intercambio de visibilidad?
6. ¿Quién administrará el contenido y atenderá reservas?
7. ¿Existe ya un sitio web o redes sociales del museo con las que deba integrarse la landing?
8. ¿Cuál es el presupuesto disponible para diseño, desarrollo y difusión?

## 18. Roadmap posterior al MVP

- Venta de boletos y paquetes en línea con pasarela de pago.
- Versión en inglés.
- Panel de aliados para gestionar sus promociones.
- Códigos QR para canje de beneficios y medición de resultados.
- Programa de membresía o visitante frecuente.
- Mapa interactivo de ruta cultural por Torreón.
- Integración con CRM y campañas automatizadas.

---

*Documento vivo: se actualizará conforme se validen datos con el museo y se definan alianzas.*
