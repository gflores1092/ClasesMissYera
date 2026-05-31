# 📦 MATERIALES DE DEMO — qué usar en cada bloque

Todo lo que necesitas para grabar. Cada material va con su bloque y su prompt exacto.

---

## BLOQUE 1 · Artifacts (Construye)
**Archivo:** `01_encuesta_satisfaccion.xlsx`
**Qué haces:** arrástralo al chat de Claude.
**Prompt:** *"Te paso los resultados de una encuesta de satisfacción (anonimizada). Analízalos y constrúyeme un tablero interactivo de UNA página que muestre: (1) promedio por curso, (2) los que están en alerta (por debajo de 70), y (3) la evolución por periodo. Hazlo visual y fácil de leer."*
Luego: *"Resáltame en otro color los que están por debajo de 70."* y *"Agrega un filtro por área."*

> Datos pensados a propósito: el **Curso C** cae (68→64→61) y el **Curso E** está al límite (70). Eso te da el "momento ajá" de los cursos en alerta. El Curso D va subiendo (buen contraste).

---

## BLOQUE 2 · Projects (Recuerda)
**Archivos:** `02_guia_de_estilo.md` + `02_comunicados_modelo.md`
**Qué haces:** crea el Project "Comunicaciones institucionales", pega el texto de instrucciones (está en el runbook) y sube estos dos archivos.
**Prompt para el contraste (úsalo fuera y dentro del Project):** *"Redacta un comunicado para estudiantes sobre el inicio del periodo de matrícula."*

> Fuera del Project sale genérico. Dentro, sale con el formato y el tono de los modelos. Esa es la demostración.

---

## BLOQUE 3 · Skills (Aprende tu método)
**Archivos:** la skill `acta-de-reunion` (carpeta con SKILL.md) + `03_notas_reunion.md`
**Qué haces:** instala la skill, luego pega el contenido de `03_notas_reunion.md`.
**Prompt:** *"Conviérteme estas notas en un acta."*

> Las notas vienen desordenadas a propósito y con datos faltantes. La skill debe armarte el acta con la tabla de acuerdos, poner responsables/fechas, y marcar como `[POR DEFINIR]` lo que falta (fecha del taller, responsable del reglamento, monto). Ese detalle —que NO inventa— es lo que impresiona.
> Para el contraste "sin skill", pega las mismas notas en un chat sin la skill y muestra que lo hace a su manera.

---

## BLOQUE 4 · Connectors (Se conecta)
**Material:** NINGUNO que yo pueda darte — aquí usas TUS cuentas reales.
**Qué haces ANTES de grabar:** conecta Outlook y Calendar/Teams en Configuración → Conectores.
**Prompts:** *"Revisa mi correo de hoy en Outlook y dime solo lo urgente, en 3 bullets."* · *"¿Qué reuniones tengo esta semana? Resúmemelo por día."* · *"Busca en mi OneDrive el archivo [pon un archivo real tuyo] y dime de qué trata."*

> Reemplaza `[NOMBRE]` por un archivo que de verdad tengas en tu OneDrive, para que la búsqueda funcione en vivo.

---

## SKILLS EXTRA (no son del video, pero te las dejo para usar)
- `comunicado-institucional` — redacta anuncios formales completos.
- `resumen-ejecutivo` — convierte un documento largo en TL;DR + puntos + riesgos + acciones.

---

## ✅ Checklist final antes de grabar
- [ ] `01_encuesta_satisfaccion.xlsx` descargado y a la mano.
- [ ] Project creado, instrucciones pegadas, `02_guia_de_estilo.md` y `02_comunicados_modelo.md` subidos.
- [ ] Skill `acta-de-reunion` instalada + `03_notas_reunion.md` listo para pegar.
- [ ] Outlook / Teams / OneDrive conectados y con un archivo real elegido para la búsqueda.
- [ ] Modelo tope de Claude verificado.
- [ ] Runbook (`clase-claude-4-bloques-runbook.md`) abierto al lado + diapositivas (`Claude-4-bloques.pptx`).
