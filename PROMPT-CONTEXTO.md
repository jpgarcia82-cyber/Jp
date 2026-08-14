# Contexto del proyecto — Cimiento

Este documento resume todo lo decidido y construido hasta ahora, para continuar el trabajo en otra herramienta o sesión sin perder contexto. Pégalo completo como primer mensaje.

---

## Quién soy y qué vendo

Soy un consultor independiente. Ayudo a PYMEs mexicanas que hoy operan de forma artesanal (Excel, WhatsApp, correo, sin sistema real) a pasar a un negocio con datos: un sistema implementado de verdad, con visibilidad financiera real y verificable.

**Lo que vendo, exactamente:**
- Mi metodología propia de 4 fases (ver abajo).
- Mi experiencia implementando sistemas — hoy trabajo sobre ERPNext como sistema de registro.
- Automatización a la medida de cada cliente (no tengo un producto de automatización propio empaquetado — se diseña y construye caso por caso).

**Lo que NO vendo — corrección importante que ya se aplicó en todo lo generado:**
"TINO" es el motor de automatización de un cliente actual (un proyecto real, en producción) — **es de ese cliente, no mío**. No se menciona en ningún material de marketing como tecnología propia. Si en algún momento aparece TINO en una versión vieja de algún archivo, es un error a corregir.

**Tampoco me caso con ERPNext como identidad de marca.** Es la herramienta con la que resuelvo el sistema de registro hoy, no un compromiso permanente. La marca y el mensaje central se apoyan en la metodología y en la verificación (auditoría v1/v2), no en el nombre de ninguna herramienta específica. Donde se menciona ERPNext en el copy, está enmarcado como "hoy, sobre ERPNext" — nunca como parte del nombre o la tagline principal.

## El problema que resuelvo

La mayoría de las PYMEs no saben en qué canal ganan dinero, en cuál pierden, cuánto les cuesta adquirir un cliente, ni si están reteniendo o solo reemplazando clientes que se van. Todo vive disperso entre Excel, correos y WhatsApp que nadie audita. Entrego un sistema real, no una recomendación en PDF.

## La metodología (4 fases)

**01 · Diagnóstico** (parte del pago único de setup) — Auditoría técnica real de lo que existe hoy, más el mapeo del customer journey ACTUAL sobre el framework AARRR. Entregable: documento de auditoría v1.

**02 · Diseño** (setup) — Journey deseado end-to-end sobre el mismo framework, más el diccionario de KPIs financieros.

**03 · Implementación** (setup, con Gantt visible) — Se construye de verdad: el sistema de registro (hoy, ERPNext), la automatización a la medida. Entregable: sistema funcionando + auditoría v2 que certifica que todo quedó conectado.

**04 · Monitoreo** (aquí vive la mensualidad) — Dashboards vivos con KPIs reales, reporte por ciclo con hallazgos basados en datos reales. Si el cliente deja de pagar, se detiene el servicio de ajustes.

**El diferenciador central: la comparación auditoría v1 vs. v2 es la prueba de que el sistema funciona — no una promesa, un documento verificable.**

## Precios de referencia usados en el modelo financiero

Setup: $100,000 MXN (pago único). Mensualidad de monitoreo: $30,000 MXN/mes.

## Posicionamiento

**Frase central:** "No te vendo un reporte. Te instalo un sistema que audita tu negocio antes y después — y te dice, con datos, en qué canal ganas y en cuál pierdes."

**Hook actual de la landing (nuevo, reemplaza al anterior):** "¿Cansado de tu consultor? Somos tu estrategia." — funciona como puente para dos audiencias: quien nunca tuvo consultor (opera a ciegas) y quien ya tiene uno con el que está insatisfecho (le pide un reporte que nadie revisa).

**Objeciones ya resueltas en el copy:** precio (se reposiciona qué se compra, no se compite por barato), "¿esto es muy técnico para mí?" (nunca tocas el sistema, todo pasa por tu aprobación), "¿y si no funciona?" (la comparación v1/v2 es la prueba, no la promesa).

## Marca

**Nombre:** Cimiento. Razonamiento: no hay tecnología propia sobre la cual construir marca (TINO no es mío), así que el nombre carga solo con la metodología y la especialización — funciona como "Cimiento — estrategia y sistemas de datos para PYMEs" sin nombrar ninguna herramienta en la tagline. Otras opciones consideradas (con su razonamiento) están en `marca-y-posicionamiento.md`: Bitácora, Andamio, Trama.

**Dirección visual:** concepto de auditoría/contaduría/bitácora física, no SaaS genérico. Paleta: negro cálido `#16140f`, papel `#F2EFE6`, panel `#EAE5D6`, acento rojo de sello `#C1391F`, verde de "verificado" `#2F5233`. Tipografía: Archivo (titulares) + IBM Plex Mono (datos/etiquetas). Cero esquinas redondeadas, líneas finas tipo hoja contable, sello circular como ícono de marca. Se evita explícitamente: gradiente morado, Inter/Space Grotesk, crema+serif+terracota, tarjetas redondeadas — el look genérico de IA.

## Archivos ya generados (adjúntalos junto con este prompt)

- **`marca-y-posicionamiento.md`** — brief completo de posicionamiento, naming (con razonamiento de cada opción) y dirección visual.
- **`landing/index.html`** — landing principal, un solo archivo HTML, diseño terminado y revisado visualmente.
- **`landing/diagnostico.html`** — autodiagnóstico gratuito de 9 preguntas (self-serve), sin IA, sin costo, sin datos sensibles. Genera un resultado por niveles (bajo/medio/alto riesgo de "operar a ciegas") con CTA hacia la auditoría completa paga. Enlazado desde la landing como CTA principal.
- **`modelo-mercado-pymes-mexico.xlsx`** — modelo de mercado bottom-up con fórmulas en vivo, 7 hojas: Fuentes (datos de INEGI/DENUE/ENAPROCE separados de supuestos editables), Via A (servicios de proyecto), Via B (restaurantes), Resumen (SOM total, capacidad como consultor solo, filtro de quién puede pagar $100k+$30k/mes), Sensibilidad (3 escenarios), Valoracion (proyección de ingresos + rango de valor del negocio), Escala30M (qué se necesita para llegar a $30M MXN/año de ingreso).

## Hallazgos clave del modelo de mercado (para no recalcular desde cero)

- Universo total de unidades económicas privadas en México: 5,451,113 (INEGI, Censos Económicos 2024).
- Mercado obtenible servible (SOM) estimado, escenario base: **~9,018 negocios** calificados y direccionables a nivel nacional, sumando dos vías: servicios de proyecto (SCIAN 54, ~4,659) y restaurantes (~4,359).
- De esos, ~**3,156** pueden pagar cómodamente el ticket de $100k setup + $30k/mes (supuesto del 35%, marcado como el número menos sólido del modelo — falta dato real de distribución de ingresos dentro de la banda Pequeña/Mediana).
- Mi capacidad real como consultor solo: ~1.5 clientes nuevos instalados por trimestre, techo de ~18 en cartera de monitoreo antes de necesitar contratar.
- Para llegar a $30M MXN/año de ingreso hacen falta ~83 clientes en cartera simultánea, lo que implica ~5 operadores equivalentes (yo + 4) y una trayectoria de ~6 años contratando ~1 operador/año. El mercado no es el cuello de botella (se necesita <1% del SOM) — el cuello de botella es operativo (pasar de consultor solo a equipo sin perder la calidad verificable del trabajo). Ese modelo no incluye costos/márgenes, solo ingreso agregado.

## Estado actual del embudo

Landing (`index.html`) → CTA principal lleva al autodiagnóstico gratuito (`diagnostico.html`, 9 preguntas, cero IA, cero costo) → resultado por niveles con CTA hacia auditoría completa paga (mailto directo, sin backend). CTA secundario en ambas páginas para agendar llamada directo por correo.

## Pendiente / próximo paso (decisión ya tomada: no avanzar todavía)

Se evaluó construir una versión del autodiagnóstico con un agente de Claude (Anthropic) que redactara el resultado en lenguaje natural en vez de plantillas. Se decidió **NO hacerlo por ahora** — la versión sin IA ya funciona y es gratis; se quiere validar el embudo primero. Si se retoma:
- Usar Claude Haiku (el modelo más barato), una sola llamada por diagnóstico completado usando las mismas 9 respuestas ya recolectadas — costo estimado de centavos por lead, no dólares.
- Requiere backend mínimo (ej. Cloudflare Worker o función serverless) para guardar la API key — **nunca exponerla en el HTML público**, cualquiera podría robarla del código fuente.
- No convertir esto en una conversación abierta tipo chat: mantener el intake estructurado (cerrado, sin texto libre) para no romper la promesa de "no datos sensibles" y para mantener el costo predecible.

## Restricciones que hay que seguir respetando

- No inventar precios exactos, testimonios, ni nombres de clientes reales — usar placeholders explícitos donde falte el dato.
- No mencionar TINO como tecnología propia.
- No casar la identidad de marca con ERPNext específicamente.
- El autodiagnóstico no debe pedir datos financieros reales, contraseñas, ni información de clientes del prospecto.
- Evitar el look genérico de IA en cualquier diseño nuevo (ver paleta/tipografía arriba).
