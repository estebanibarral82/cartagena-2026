# Itinerario Cartagena de Indias — Familia Ibarra
## Especificación completa para webapp interactiva (GitHub Pages)

---

## 🎯 OBJETIVO

Crear una webapp HTML/CSS/JS single-file (`index.html`) mobile-first, visualmente premium, para usarla como guía de viaje familiar en el celular. Debe funcionar como PWA (agregar a pantalla de inicio) y no requerir backend. Publicar en GitHub Pages.

La experiencia UX/UI debe ser extremadamente amigable, pensada para que cualquier miembro de la familia (incluida la esposa, que no es necesariamente tech-savvy) pueda navegar fácilmente.

---

## 📋 DATOS GENERALES DEL VIAJE

- **Destino:** Cartagena de Indias, Colombia
- **Viajeros:** Familia Ibarra — 4 personas (Esteban, esposa, hijos de 12 y 19 años)
- **Hotel:** Radisson Cartagena Ocean Pavillion
- **Fechas:** 19 al 28 de Febrero 2026 (9 noches, 10 días)
- **Desayuno incluido** todos los días en el hotel
- **Operadores locales:**
  - **Natal Travel Cartagena** (Tour Histórico + Traslados)
    - Web: https://nataltravelcartagena.com/
    - Valoraciones TripAdvisor: https://www.tripadvisor.com/Attraction_Review-g297476-d16672954-Reviews-Natal_Concierge-Cartagena_Cartagena_District_Bolivar_Department.html
    - **Contacto:** Carlos | WhatsApp: +57 310 703 7903
  - **Botes y Yates Cartagena** (Islas del Rosario)
    - Instagram: https://www.instagram.com/botesyates_cartagena/
    - Valoraciones TripAdvisor: https://www.tripadvisor.cl/Attraction_Review-g297476-d27491804-Reviews-Botes_y_Yates_Cartagena-Cartagena_Cartagena_District_Bolivar_Department.html
    - **Contacto:** Catalina

---

## ✈️ VUELOS (Avianca — escala en Bogotá)

### IDA — Jueves 19 de Febrero
| Tramo | Vuelo | Salida | Llegada |
|-------|-------|--------|---------|
| Santiago → Bogotá | AV0098 | 07:25 | 11:45 |
| *Escala en Bogotá* | — | *2h 25min* | — |
| Bogotá → Cartagena | AV9772 | 14:10 | 15:40 |

### VUELTA — Sábado 28 de Febrero
| Tramo | Vuelo | Salida | Llegada |
|-------|-------|--------|---------|
| Cartagena → Bogotá | AV9747 | 18:20 | 20:00 |
| *Escala en Bogotá* | — | *1h 35min* | — |
| Bogotá → Santiago | AV0097 | 21:35 | 05:30 (1 Mar) |

---

## 🗓️ ITINERARIO DÍA A DÍA

La distribución alterna días de actividad con días de descanso para mantener el ritmo familiar. Los 4 tours/actividades están distribuidos estratégicamente con descanso entre cada uno.

**Patrón:** Tour → Playa/Isla → Libre → Chocolate+Compras → Libre → Libre → Cultural+Atardecer → Libre

---

### DÍA 1 — Jueves 19 Feb · LLEGADA
**Tipo:** ✈️ Viaje
- Vuelo SCL → BOG → CTG (llegada 15:40)
- Traslado aeropuerto → hotel
- Check-in desde las 15:00
- Descanso y cena libre en Bocagrande
- **Horario:** 07:25 – 17:00
- **Costo:** Incluido en paquete de actividades
- **Tip:** Aprovechen de caminar por el malecón de Bocagrande al atardecer para ir conociendo la zona

---

### DÍA 2 — Viernes 20 Feb · 🎭 TOUR LITERARIO GARCÍA MÁRQUEZ
**Tipo:** 🎭 Tour cultural
- Tour privado a pie por el casco histórico con Nexperience
- Recorrido literario por los escenarios de Gabo: Camellón de los Mártires, Plaza Cervantes, Parque San Diego, Teatro Adolfo Mejía
- Incluye bebida de bienvenida y recogida en hotel
- **Itinerario del tour:**
  1. Camellón de los Mártires — Llegada de García Márquez a la ciudad
  2. Plaza Cervantes — La historia del periodista "Gabo"
  3. Calle del Tablón — Primeros años de vida en Cartagena
  4. Calle Primera de Badillo — Conexiones con la historia de Gabo
  5. Parque Fernández de Madrid — Historias y libros con la Iglesia de Santo Toribio de fondo
  6. Parque San Diego — Escenarios de sus libros cobran vida
  7. La Serrezuela — La antigua plaza de toros y su historia
  8. Teatro Adolfo Mejía — Legado final de García Márquez
- **Horario:** 09:00 – 11:30 (2.5 horas)
- **Costo:** $130 USD (familia completa, incluye guía privado y bebidas)
- **Tarde libre:** Explorar las murallas por cuenta propia, helados, fotos
- **Link info tour:** https://nexperience.com.co/tour-privado-a-pie-gabriel-garcia-marquez/
- **Tip:** El teatro Adolfo Mejía es espectacular por dentro. Lleven cámara. La tarde es ideal para recorrer las murallas al propio ritmo.

---

### DÍA 3 — Sábado 21 Feb · 🏝️ ISLAS DEL ROSARIO — LANCHA PRIVADA + BEACH CLUB
**Tipo:** 🏝️ Playa & aventura
- Día completo en lancha privada con Botes y Yates Cartagena (Catalina)
- Ruta: Marina → Isla Grande → Tour panorámico → Rosario de Mar Beach Club → Barú (opcional) → Marina
- Estadía en Rosario de Mar Beach Club
- **La lancha privada incluye:**
  1. Capitán experto y asistente
  2. Combustible
  3. Freezer + 15 kg de hielo
  4. Sistema de sonido
  5. Asoleadoras
  6. Baño a bordo
  7. Snorkeling
  8. Acceso al Beach Club Rosario de Mar
- **Almuerzo NO incluido** (se paga directamente en el beach club, ~$30-50 USD)
- **Horario:** 09:00 – 17:00 (día completo)
- **Costo:** $200 USD (lancha privada, 4 personas)
- **Fotos y videos del lugar:** La carpeta `source/rosario` contiene fotos y videos de las Islas del Rosario. **IMPORTANTE: Usar estas imágenes/videos en una galería o carousel dentro de la card de este día.** Revisa los archivos en la carpeta y embebe las fotos directamente en el HTML. Si son videos, incluirlos como `<video>` con controles.
- **Links:**
  - Instagram Botes y Yates: https://www.instagram.com/botesyates_cartagena/
  - Valoraciones TripAdvisor: https://www.tripadvisor.cl/Attraction_Review-g297476-d27491804-Reviews-Botes_y_Yates_Cartagena-Cartagena_Cartagena_District_Bolivar_Department.html
- **Tip:** La experiencia de lancha privada es única. Lleven snacks extra, protector solar y cámara acuática. El snorkel en el archipiélago es espectacular con aguas cristalinas.

---

### DÍA 4 — Domingo 22 Feb · 😎 DÍA LIBRE
**Tipo:** 🌴 Descanso
- Descanso post-isla
- Piscina del hotel, playa en Bocagrande
- Opción: pasear por Centro Comercial La Serrezuela (aire acondicionado, tiendas, gastronomía)
- **Costo:** $0 (desayuno incluido)
- **Tip:** La Serrezuela queda en el centro amurallado y tiene una terraza en el último piso con vista panorámica. Ideal para almorzar.

---

### DÍA 5 — Lunes 23 Feb · 🍫 MUSEO DEL CHOCOLATE + COMPRAS
**Tipo:** 🎭 Cultural + shopping
- **Mañana:** Museo del Chocolate
  - Dirección: Calle del Curato #38-99
  - Entrada gratuita
  - Talleres de chocolate: $12-25 USD
  - Web: https://museodelchocolate.com.co/cartagena/
- **Tarde:** Shopping
  - Plaza Bocagrande
  - La Serrezuela
  - Las Bóvedas (artesanías y souvenirs)
- **Horario:** 10:00 – 18:00
- **Costo:** $30 USD (talleres + compras estimadas)
- **Tip:** Las Bóvedas son las antiguas bóvedas militares de la muralla convertidas en tiendas de artesanías. Buen lugar para souvenirs, pero siempre regateen. El museo del chocolate es interactivo y divertido para toda la familia.

---

### DÍA 6 — Martes 24 Feb · 😎 DÍA LIBRE
**Tipo:** 🌴 Descanso
- Día libre sin actividades programadas
- Opción: recorrer barrio Manga (arquitectura colonial, tranquilo)
- Opción: piscina del hotel y playa en Bocagrande
- **Costo:** $0 (desayuno incluido)
- **Tip:** Manga es un barrio residencial con hermosas casas republicanas. Ideal para una caminata tranquila por la mañana.

---

### DÍA 7 — Miércoles 25 Feb · 😎 DÍA LIBRE
**Tipo:** 🌴 Descanso
- Día libre a elección:
  - **Opción A:** Spa o masajes (el hotel puede recomendar)
  - **Opción B:** Playa en Bocagrande o piscina del hotel
  - **Opción C:** Explorar barrios (Getsemaní, San Diego, Manga)
- **Costo:** $0 (desayuno incluido)
- **Tip:** Es el día perfecto para descansar y volver a ese rincón que más les gustó.

---

### DÍA 8 — Jueves 26 Feb · 🏰 TOUR HISTÓRICO + GETSEMANÍ + CAFÉ DEL MAR
**Tipo:** 🎭 Cultural + experiencia
- **Tour histórico con Natal Travel** (operador oficial):
  - La mejor manera de conocer y palpar la historia de Cartagena contada paso a paso por guías profesionales
  - Adentrarse en los túneles del imponente Castillo de San Felipe de Barajas
  - Explorar cada rincón del pintoresco barrio de Getsemaní
  - Las empedradas calles de la ciudad amurallada y admirar su arquitectura
  - Una experiencia interesante e inolvidable
  - **Duración:** 4 horas, horario flexible
  - **Incluye:**
    - Guía profesional bilingüe
    - Transporte privado
    - Tickets de entrada al Castillo de San Felipe de Barajas
- **Atardecer:** Café del Mar sobre las murallas (icónico de Cartagena)
- **Noche:** Cena especial de despedida en Getsemaní
- **Horario:** 09:00 – 21:00
- **Costo:** $80 USD (tour completo + consumo Café del Mar, 4 personas)
- **Links:**
  - Info del tour: https://nataltravelcartagena.com/experiencias.html
  - Valoraciones Natal Travel: https://www.tripadvisor.com/Attraction_Review-g297476-d16672954-Reviews-Natal_Concierge-Cartagena_Cartagena_District_Bolivar_Department.html
- **Tip:** Recorran los túneles del castillo, son fascinantes. Lleguen a Café del Mar a las 17:00 para buena mesa. El atardecer en la muralla es el mejor cierre del viaje. Reservar Café del Mar con anticipación.

---

### DÍA 9 — Viernes 27 Feb · 😎 DÍA LIBRE — ÚLTIMO DÍA COMPLETO
**Tipo:** 🌴 Descanso
- Compras finales, última pasada por el centro histórico
- Disfrutar piscina del hotel
- Preparar maletas
- **Costo:** $0 (desayuno incluido)
- **Tip:** Disfruten sin prisa. Es el último día completo en Cartagena.

---

### DÍA 10 — Sábado 28 Feb · REGRESO
**Tipo:** ✈️ Viaje
- Check-out hasta 12:00
- Mañana libre (piscina, últimas compras)
- Traslado al aeropuerto ~16:00
- Vuelo CTG → BOG → SCL (llegada 05:30 del 1 de Marzo)
- **Costo:** Incluido en paquete de actividades
- **Tip:** Dejen las maletas en conserjería después del check-out y aprovechen la piscina hasta las 15:00. Llegar al aeropuerto a las 16:00.

---

## 💰 RESUMEN DE COSTOS — ACTIVIDADES Y TOURS

| Actividad | Costo (4 personas) |
|-----------|-------------------|
| Traslados aeropuerto (ida + vuelta) | $40 USD |
| Tour García Márquez — Nexperience | $130 USD |
| Islas del Rosario — Botes y Yates Cartagena (lancha privada + Beach Club) | $200 USD |
| Museo del Chocolate + Compras | $30 USD |
| Tour Histórico + Getsemaní + Café del Mar | $80 USD |
| **TOTAL** | **$480 USD** |

*Todos los días incluyen desayuno en el hotel. Vuelos y hotel no incluidos en este presupuesto.*
*Nota: Almuerzo en Islas del Rosario no incluido (~$30-50 USD adicionales, se paga en Rosario de Mar Beach Club).*

---

## 🌤️ CLIMA EN CARTAGENA — FEBRERO 2026

Datos climáticos promedio para el período del viaje (19-28 Feb):

| Dato | Valor |
|------|-------|
| Temperatura máxima | 31°C – 32°C (88°F – 90°F) |
| Temperatura mínima | 24°C – 25°C (75°F – 77°F) |
| Sensación térmica | ~38°C (100°F) — calor húmedo |
| Horas de sol | 9 – 10 horas/día |
| Lluvia | Casi nula (mes más seco del año, ~3mm total) |
| Humedad | 66% – 71% |
| Temperatura del mar | 27°C (81°F) — perfecta para nadar |
| Amanecer / Atardecer | 06:16 – 18:12 |
| Índice UV | Alto (7) — usar protector solar siempre |

**Resumen:** Febrero es el mes más seco y soleado de Cartagena. Calor tropical con brisa. Ideal para playa. Llevar ropa muy ligera, protector solar alto SPF, sombrero y mantenerse hidratados.

---

## 💱 CONVERSOR DE MONEDA

Incluir un **conversor de moneda interactivo** en la webapp con las siguientes características:

### Conversiones soportadas:
- **CLP ↔ COP** (Peso Chileno a Peso Colombiano)
- **USD ↔ COP** (Dólar a Peso Colombiano)
- **CLP ↔ USD** (Peso Chileno a Dólar)

### Tasas de referencia (Febrero 2026, aproximadas):
- 1 CLP = 4.25 COP
- 1 USD = 4,200 COP
- 1 USD = 988 CLP

### UX del conversor:
- Input numérico grande y fácil de usar con el teclado del celular (`inputmode="decimal"`)
- Selector de moneda origen y destino con banderas (🇨🇱 🇨🇴 🇺🇸)
- Resultado en tiempo real mientras se escribe
- Botón para invertir la conversión (swap ↕️)
- Nota al pie: "Tasas referenciales Feb 2026. Verificar al momento de cambiar."
- Shortcuts con montos comunes: 10.000 CLP | 50.000 CLP | 100.000 COP | 50 USD

---

## 📅 AGREGAR A GOOGLE CALENDAR

Incluir un **botón "📅 Agregar al calendario"** en cada día de actividad (días 1, 2, 3, 5, 8, 10).

### Formato del link de Google Calendar:
```
https://calendar.google.com/calendar/render?action=TEMPLATE&text={TÍTULO}&dates={INICIO}/{FIN}&details={DETALLE}&location=Cartagena+de+Indias,+Colombia
```

### Eventos a generar:

1. **Vuelo ida SCL→CTG** (Día 1)
   - Título: ✈️ Vuelo Santiago → Cartagena
   - Fecha: 20260219T072500 / 20260219T154000
   - Detalle: AV0098 SCL 07:25→BOG 11:45 | Escala 2h25 | AV9772 BOG 14:10→CTG 15:40

2. **Tour García Márquez** (Día 2)
   - Título: 🎭 Tour García Márquez — Nexperience
   - Fecha: 20260220T090000 / 20260220T113000
   - Detalle: Tour privado a pie por casco histórico. Incluye bebida y recogida en hotel.
   - Location: Centro Histórico, Cartagena de Indias, Colombia

3. **Islas del Rosario** (Día 3)
   - Título: 🏝️ Islas del Rosario — Lancha Privada
   - Fecha: 20260221T090000 / 20260221T170000
   - Detalle: Lancha privada Botes y Yates Cartagena. Ruta: Marina → Isla Grande → Rosario de Mar Beach Club → Barú (opcional) → Marina. Incluye capitán, snorkel, sonido, hielo. Almuerzo no incluido.
   - Location: Islas del Rosario, Cartagena, Colombia

4. **Museo del Chocolate + Compras** (Día 5)
   - Título: 🍫 Museo del Chocolate + Compras
   - Fecha: 20260223T100000 / 20260223T180000
   - Detalle: Mañana: Museo del Chocolate (Calle del Curato #38-99, entrada gratis, talleres $12-25 USD). Tarde: Shopping en Plaza Bocagrande, La Serrezuela, Las Bóvedas.
   - Location: Centro Histórico, Cartagena de Indias, Colombia

5. **Tour Histórico + Café del Mar** (Día 8)
   - Título: 🏰 Tour Histórico + Café del Mar
   - Fecha: 20260226T090000 / 20260226T210000
   - Detalle: Castillo San Felipe + Getsemaní + atardecer Café del Mar. Incluye guía bilingüe, transporte y entradas.
   - Location: Castillo de San Felipe de Barajas, Cartagena, Colombia

6. **Vuelo vuelta CTG→SCL** (Día 10)
   - Título: ✈️ Vuelo Cartagena → Santiago
   - Fecha: 20260228T182000 / 20260301T053000
   - Detalle: AV9747 CTG 18:20→BOG 20:00 | Escala 1h35 | AV0097 BOG 21:35→SCL 05:30 (1 Mar)

### UX del botón:
- Botón pequeño y discreto dentro de cada card de actividad
- Ícono de calendario + texto "Agregar al calendario"
- Al tocar, abre Google Calendar en nueva pestaña con el evento prellenado
- Color sutil, no compite con el contenido principal

---

## 📌 INFORMACIÓN ÚTIL

- **Hotel:** Radisson Cartagena Ocean Pavillion | Check-in 15:00 / Check-out 12:00
- **Desayuno:** Incluido todos los días en el hotel
- **Qué llevar:** Protector solar SPF 50+, sombreros, ropa muy ligera, zapatos cómodos para calles empedradas, traje de baño, toalla de playa, cámara acuática
- **Café del Mar:** Reservar con anticipación para el atardecer (llegar 17:00)
- **Moneda:** Peso colombiano (COP). Se acepta USD en muchos lugares turísticos. Llevar efectivo para artesanías.
- **Propinas:** 10% en restaurantes (a veces incluida). Dar propina a guías y lancheros.
- **Hidratación:** Beber mucha agua. Calor húmedo constante (~38°C sensación térmica).
- **Enchufe:** Tipo A/B (mismo que en USA). Si llevan cargadores chilenos (tipo C), necesitarán adaptador.

---

## 📞 CONTACTO OPERADORES LOCALES

**Carlos — Natal Travel Cartagena** (Tour Histórico + Traslados)
- WhatsApp: [+57 310 703 7903](https://wa.me/573107037903)
- Web: [nataltravelcartagena.com](https://nataltravelcartagena.com/)
- TripAdvisor: [Ver valoraciones](https://www.tripadvisor.com/Attraction_Review-g297476-d16672954-Reviews-Natal_Concierge-Cartagena_Cartagena_District_Bolivar_Department.html)

**Catalina — Botes y Yates Cartagena** (Islas del Rosario)
- Instagram: [botesyates_cartagena](https://www.instagram.com/botesyates_cartagena/)
- TripAdvisor: [Ver valoraciones](https://www.tripadvisor.cl/Attraction_Review-g297476-d27491804-Reviews-Botes_y_Yates_Cartagena-Cartagena_Cartagena_District_Bolivar_Department.html)

---

## 🎨 ESPECIFICACIONES DE DISEÑO PARA LA WEBAPP

### Requisitos técnicos
- **Single file:** Todo en un solo `index.html` (HTML + CSS + JS inline)
- **Mobile-first:** Diseñada para verse perfecta en celular (375px–430px principal)
- **PWA ready:** Meta tags para "agregar a pantalla de inicio"
- **Sin dependencias externas** excepto Google Fonts y Material Symbols
- **Funciona offline** una vez cargada (todo autocontenido)
- **GitHub Pages compatible:** Solo archivos estáticos
- **Fotos de Islas del Rosario:** Embeber directamente las imágenes y videos de la carpeta `source/rosario` en el HTML (como base64 o referencia relativa si se sube al mismo repo). Beach club: Rosario de Mar.

### Diseño visual
- **Estética:** Tropical premium. Elegante pero cálida, no genérica.
- **Paleta de colores:**
  - Arena/fondo: `#F5F0E8`
  - Océano (primario): `#0A6E78`
  - Coral (acento): `#E8654A`
  - Dorado (detalles): `#D4A853`
  - Noche (textos oscuros): `#1A2332`
- **Tipografía:** Google Fonts — `DM Serif Display` para títulos, `DM Sans` para cuerpo
- **Iconos:** Material Symbols Rounded (Google)
- **Border radius:** 16px en cards, 100px en chips/badges
- **Animaciones:** Suaves, no agresivas. Fade-in con stagger, transiciones de 0.3s

### Estructura de la webapp — SECCIONES CON TABS

#### 1. Hero section (header visual)
- Gradiente océano/dorado con efecto de onda sutil CSS
- Título "Cartagena de Indias" en tipografía serif grande
- Badge con fechas "19 FEB — 28 FEB 2026"
- Subtítulo: "Familia Ibarra · 4 personas · Radisson Ocean Pavillion · 9 noches"

#### 2. Stats bar (chips horizontales con scroll)
- 10 días | 9 noches | Desayuno incluido | $480 USD | ☀️ 31°C

#### 3. Navegación por tabs (sticky al scrollear)
Tabs: **Itinerario** | **Vuelos** | **Costos** | **Clima** | **Conversor** | **Info útil**

#### 4. Sección Itinerario
- Cards por día, colapsables (tap para expandir/contraer, solo una abierta a la vez)
- Cada card muestra: número de día con color por tipo, fecha en español, título, chevron animado
- Al expandir:
  - Descripción detallada
  - Horario, qué incluye, tips
  - **Links externos** como botones/badges clickeables: "🌐 Ver en web", "⭐ TripAdvisor", "🍽️ Ver menú"
  - **Botón 📅 "Agregar al calendario"** (solo días con actividad)
  - **Galería de fotos/videos** para Islas del Rosario (Día 3) — carousel touch-friendly

#### 5. Sección Vuelos
- 2 cards (ida/vuelta) con ruta visual SCL → BOG → CTG
- Botón 📅 en cada vuelo

#### 6. Sección Costos
- Tabla de costos con links a webs de cada actividad
- Total $480 USD destacado

#### 7. Sección Clima
- Datos visuales con iconos (sol, termómetro, gota, etc.)
- Recomendaciones de qué llevar
- "Febrero es el mes más seco y soleado"

#### 8. Sección Conversor de Moneda
- Input grande, selector con banderas, resultado en tiempo real
- Botón swap, shortcuts de montos comunes
- Tasas: 1 CLP ≈ 4.25 COP | 1 USD ≈ 4,200 COP | 1 USD ≈ 988 CLP

#### 9. Sección Info útil
- Cards con datos del hotel, qué llevar, tips, enchufes
- Cards de contacto de operadores: Carlos — Natal Travel (WhatsApp + web + TripAdvisor) y Catalina — Botes y Yates Cartagena (Instagram + TripAdvisor)

### Meta tags PWA
```html
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#0A6E78">
```

---

## 📸 ASSETS — FOTOS Y VIDEOS DE ISLAS DEL ROSARIO

Las fotos y videos están en:
```
/Users/eibarr01/Downloads/Cartagena/source/rosario
```

**Instrucciones para Claude Code:**
1. Lee todos los archivos de imagen y video en esa carpeta
2. Para imágenes: conviértelas a base64 y embébelas en el HTML, o súbelas al repo como archivos y referenciarlas con ruta relativa (preferido)
3. Para videos: embébelos como `<video>` con controles, poster, autoplay=false, muted para preview
4. Crea un carousel/galería visual dentro de la card del Día 3 (Islas del Rosario — Rosario de Mar Beach Club)
5. El carousel debe ser touch-friendly (swipeable en móvil)
6. Diseño: thumbnails redondeados, indicador de dots para posición

---

## ⚠️ RESTRICCIONES IMPORTANTES

1. **NO incluir** información sobre miedos o fobias de ningún viajero
2. Los costos son los del cuadro de resumen ($480 USD total). No mostrar rangos, solo valores fijos.
3. Tono aspiracional, cálido y positivo en todas las descripciones
4. Traslados aeropuerto incluidos en el presupuesto general
5. UX extremadamente fácil para alguien no tech-savvy
6. Links externos se abren en nueva pestaña (`target="_blank"`)
7. Conversor usa tasas fijas (no requiere API)
8. Botones de Google Calendar generan el link dinámicamente (no requiere API)
9. El archivo final debe ser un solo `index.html` autocontenido (excepto imágenes del repo)
