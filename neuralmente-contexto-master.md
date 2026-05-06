# NeuralMente — Documento de Contexto Master
## Usa este documento al inicio de cada conversación nueva con Claude

---

## QUÉ ES NEURALMENTE
Academia de IA 100% en español, automatizada con IA como tutor principal.
- **Website:** neuralmente.app
- **Dueño:** Elias Garcia Jr
- **Ubicación:** Los Angeles, California
- **Modelo:** Suscripción $49.99/mes con trial de 3 días (tarjeta requerida)
- **Stack:** HTML/CSS/JS estático en Vercel + GitHub

---

## DOMINIO Y HOSTING
- **Dominio:** neuralmente.app (comprado en Namecheap)
- **Hosting:** Vercel (plan gratuito)
- **Repositorio GitHub:** neuralmente (usuario: chato84)
- **DNS:** Apuntando de Namecheap a Vercel (A record: 216.198.79.1)
- **Bluehost:** Tiene cuenta pero NO se usa para NeuralMente

---

## ARCHIVOS EN GITHUB (neuralmente repo)
```
index.html          → Landing page principal
quiz.html           → Quiz de onboarding 5 preguntas (como Cursive)
precios.html        → Página de precios con Stripe
dashboard.html      → Panel de acceso (solo para el dueño)
aula-interactiva.html → Aula completa Track 1 con XP y gamificación
aula-modulo1.html   → Módulo 1 contenido profundo
video-educativo-demo.html → Demo de videos animados
tutor-demo-v2.html  → Demo del tutor IA
mapa-academia-completo.html → Los 5 tracks y 42 módulos
como-funciona-aula.html → Diagrama de arquitectura
```

## FLUJO DEL ESTUDIANTE
```
neuralmente.app → quiz.html → precios.html → Stripe → aula-interactiva.html
```

---

## STRIPE
- **Cuenta:** NeuralMente (separada de Cafe Estudio)
- **Modo:** Sandbox (hay que activar live cuando esté listo)
- **Producto:** NeuralMente Pro — $49.99/mes
- **Trial:** 3 días con tarjeta requerida
- **Payment Link:** https://buy.stripe.com/7sYfZh5i0eyleTfgM72Nq00
- **Portal cancelación:** Pendiente de activar en Settings → Billing → Customer Portal

---

## ACADEMIA — ESTRUCTURA COMPLETA
- **5 Tracks** — 42 módulos — 180+ lecciones — 28,500 XP
- **Track 1:** Fundamentos (8 módulos, 12 semanas) — ÚNICO CONSTRUIDO
- **Track 2:** IA para Negocios (9 módulos, 14 semanas)
- **Track 3:** Constructor IA — APIs, RAG, Agentes (10 módulos, 16 semanas)
- **Track 4:** Avanzado — LLMs, Fine-tuning (8 módulos, 16 semanas)
- **Track 5:** Arquitecto Master (7 módulos, 10 semanas)

## CONTENIDO CONSTRUIDO
- ✅ Módulo 1 completo con videos, quizzes, debate, brainstorm, proyecto
- ✅ Guiones de 6 videos del Módulo 1 (Word descargado)
- ✅ Video 1 "Historia de la IA" renderizado en MP4 (sin audio aún)
- ✅ Curriculum completo 42 módulos (Word descargado)
- ⏳ Módulos 2-8 del Track 1 pendientes
- ⏳ Tracks 2-5 pendientes

---

## VIDEOS
- **Herramienta:** Remotion + Claude Code
- **Proyecto:** C:\Users\Elias Garcia Jr\neuralmente-videos\
- **Video 1 renderizado:** out/historia-de-la-ia.mp4 (33.5 MB)
- **Audio pendiente:** ElevenLabs en español mexicano
- **Para agregar audio:** Poner MP3 en public/content/historia-de-la-ia/audio/ y correr npx remotion render historia-de-la-ia
- **Guiones:** Documento Word "guiones-modulo1.docx" descargado

---

## TUTOR IA
- **Motor:** Claude API (claude-sonnet-4-20250514)
- **Estado:** Demo funcional sin API key real
- **Pendiente:** Conectar API key de Anthropic
- **Costo estimado:** $0.05-0.15 por alumno por módulo
- **Característica clave:** El tutor ENSEÑA proactivamente, no solo responde preguntas
- **Modo pregunta:** Si el alumno pregunta algo fuera del tema, responde y retoma la clase

---

## COLORES Y DISEÑO
```css
--bg: #07090f        /* fondo principal */
--teal: #00d9b0      /* color principal */
--purple: #7c6cfc    /* color secundario */
--amber: #f0a935     /* XP y gamificación */
--coral: #f0634a     /* alertas y errores */
Font: Outfit (Google Fonts)
```

---

## PENDIENTES PRIORITARIOS
1. **Módulo 2** — "Cómo funciona la IA por dentro" con mismo nivel de profundidad
2. **ElevenLabs** — Voz en español mexicano para los 6 videos del Módulo 1
3. **Supabase** — Login de alumnos y base de datos
4. **Dripping** — Módulos que se desbloquean semanalmente (no todo accesible de golpe)
5. **Stripe Customer Portal** — Para que alumnos cancelen solos
6. **Claude API real** — Conectar el tutor con API key
7. **Plan gratuito** — Solo primera lección del Módulo 1, muy limitado

---

## HERRAMIENTAS Y CUENTAS
- **GitHub:** chato84 — repositorio "neuralmente"
- **Vercel:** Conectado a GitHub, deploy automático
- **Namecheap:** neuralmente.app
- **Stripe:** Cuenta NeuralMente separada
- **Remotion:** Instalado en C:\Users\Elias Garcia Jr\neuralmente-videos\
- **Claude Code:** Instalado y funcionando con Claude Pro
- **Bluehost:** cafeestudiodesigns.com (otro negocio, no usar para NeuralMente)

---

## CÓMO BRIEFEAR A CLAUDE EN CONVERSACIÓN NUEVA
Copia y pega esto al inicio:

"Estoy construyendo NeuralMente, una academia de IA en español en neuralmente.app. 
Aquí está el contexto completo del proyecto: [pega este documento]
Necesito continuar construyendo. El siguiente paso es: [di qué necesitas]"

---

## COMANDOS ÚTILES
```bash
# Ver el video en Remotion Studio
cd neuralmente-videos && npm run dev

# Renderizar video MP4
npx remotion render historia-de-la-ia

# Subir cambios a Vercel (automático via GitHub)
# Solo sube archivos a GitHub y Vercel despliega en 30 segundos
```

---

*Última actualización: Mayo 2026*
*Documento generado por Claude — NeuralMente*
