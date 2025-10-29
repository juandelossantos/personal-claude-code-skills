# 📚 Academic Task Planner Skill - Guía de Instalación y Uso

## 🎯 ¿Qué hace este Skill?

Este skill convierte automáticamente guías de aprendizaje en PDF (como las de UNAD) en checklists organizados en formato markdown con:

✅ Te pregunta cuándo vas a iniciar (no asume fechas)
✅ Tareas solo en días laborables (lunes a viernes)
✅ Respeta fines de semana - solo fechas límite críticas
✅ Tareas desglosadas con granularidad moderada
✅ Fechas específicas para cada tarea
✅ IDs únicos para cada tarea
✅ Tags personalizados (ej: #estudio #cibercultura)
✅ Cálculo automático de fecha límite del foro (3 días antes del cierre)
✅ Organización por fases/semanas
✅ Checklist de verificación final

---

## 📥 Instalación

### Opción 1: Usar directamente con Claude (Recomendado)

1. **Descarga el archivo:** `academic-task-planner_SKILL.md`

2. **En tu conversación con Claude, escribe:**
   ```
   Tengo un skill personalizado llamado "academic-task-planner".
   Te voy a compartir el archivo SKILL.md.
   Por favor léelo y aplícalo cuando suba PDFs de guías académicas.
   ```

3. **Sube el archivo** `academic-task-planner_SKILL.md`

4. **¡Listo!** Claude ahora conoce el skill y lo aplicará automáticamente.

### Opción 2: Guardar como Skill Privado en Claude Projects

1. Si estás usando Claude Projects, puedes agregar este skill a tu proyecto:
   - Ve a tu proyecto
   - Sección "Custom Instructions" o "Project Knowledge"
   - Sube el archivo `academic-task-planner_SKILL.md`

---

## 🚀 Cómo Usar

### Uso Básico

1. **Sube tu PDF** de guía de aprendizaje o tarea

2. **Pide a Claude:**
   ```
   Usa el skill academic-task-planner para crear un checklist de esta guía
   ```

3. **Claude te preguntará cuándo vas a iniciar:**
   ```
   ¿Cuándo vas a iniciar esta tarea?
   Formato: YYYY-MM-DD o "mañana" o "próximo lunes", etc.
   ```

4. **Responde con tu fecha de inicio:**
   ```
   30 de octubre
   ```
   o
   ```
   mañana
   ```

5. **Claude te preguntará por los tags:**
   ```
   ¿Qué tags quieres agregar a cada tarea?
   Ejemplo: #estudio #cibercultura #universidad
   ```

6. **Responde con tus tags:**
   ```
   #estudio #cibercultura
   ```

7. **Recibe tu checklist** en formato markdown listo para usar
   - ✅ Tareas solo en días laborables (lunes a viernes)
   - ✅ Fines de semana libres (excepto fechas límite obligatorias)
   - ✅ Fechas realistas basadas en cuándo realmente vas a empezar

### Ejemplos de Comandos

```
"Crea un plan de tareas para esta guía usando el academic-task-planner"
```

```
"Aplica el skill de planificación académica a este PDF"
```

```
"Genera un checklist organizado de esta tarea"
```

---

## 📋 Ejemplo de Salida

El skill genera un archivo markdown como este:

```markdown
# ✅ CHECKLIST Tarea 4 - Ser Digital: Habilidades para el Siglo XXI

**Periodo:** 30 de octubre - 24 de noviembre de 2025
**Valor:** 120 puntos
**⚠️ Fecha límite foro:** 21 de noviembre de 2025
**⚠️ Fecha de entrega:** 24 de noviembre de 2025

---

## 📚 SEMANA 1: Lectura y Comprensión (30 oct - 5 nov)

### 📖 Lecturas Obligatorias
- [ ] Leer artículo de Gonzales... 📅 2025-10-30 🆔 0zwo06 #estudio #cibercultura
- [ ] Leer "Retrato dual"... 📅 2025-11-01 🆔 5tyu89 #estudio #cibercultura

[... más tareas ...]
```

---

## ⚙️ Características del Skill

### ✨ Lo que hace automáticamente:

1. **Analiza el PDF completo** y extrae:
   - Fechas de inicio y cierre
   - Entregas requeridas
   - Pasos necesarios
   - Requisitos de plataforma

2. **Te pregunta cuándo VAS A INICIAR realmente:**
   - No asume que empezarás el día oficial
   - Acepta fechas o lenguaje natural ("mañana", "próximo lunes")
   - Calcula días laborables disponibles

3. **Asigna tareas SOLO a días laborables:**
   - ✅ Lunes a Viernes: tareas regulares
   - ❌ Sábado y Domingo: LIBRES
   - ⚠️ EXCEPCIÓN: Fechas límite obligatorias del foro o entrega
   - Marca con ⚠️ las fechas límite que caen en fin de semana

4. **Calcula fechas críticas:**
   - Fecha límite del foro: 3 días antes del cierre
   - Distribución equilibrada de tareas en días hábiles
   - Reserva últimos días para revisión final

5. **Organiza tareas en fases lógicas:**
   - Fase 1: Lectura y comprensión
   - Fase 2: Creación/desarrollo
   - Fase 3: Producción
   - Fase 4: Documentación y entrega

6. **Genera IDs únicos** para cada tarea (formato: `0zwo06`)

7. **Incluye verificación final** con checklist pre-entrega

### 🎯 Nivel de granularidad:

- **No muy detallado:** No micro-tareas como "abrir documento"
- **No muy general:** No tareas vagas como "completar todo"
- **Balance perfecto:** Cada tarea toma 30 min - 2-3 horas

### 📊 Cantidad de tareas según duración:

- **1-2 semanas:** 15-25 tareas
- **3-4 semanas:** 30-50 tareas
- **5+ semanas:** 50-70 tareas

---

## 🔧 Personalización

### Modificar el Skill

Si quieres ajustar el comportamiento del skill:

1. Abre `academic-task-planner_SKILL.md`
2. Busca la sección que quieres modificar
3. Edita según tus necesidades
4. Guarda y vuelve a compartir con Claude

### Secciones personalizables:

- **Task Quantity Guidelines:** Ajusta cuántas tareas por fase
- **Date Assignment Strategy:** Cambia cómo se distribuyen fechas
- **Forum Participation:** Modifica cálculo de fecha límite del foro
- **Task Categories:** Añade o elimina tipos de tareas

---

## 💡 Tips de Uso

1. **Sube PDFs claros:** El skill funciona mejor con guías estructuradas

2. **Revisa el checklist generado:** Ajusta fechas si es necesario según tu calendario personal

3. **Usa tags consistentes:** Mantén los mismos tags en todas tus tareas para mejor organización

4. **Combina con otras herramientas:**
   - Importa el markdown a Obsidian, Notion, o cualquier gestor de tareas
   - Convierte a Todoist, Trello, etc.

5. **Guarda el skill:** Mantén el archivo SKILL.md en tu biblioteca para reutilizarlo

---

## 🐛 Solución de Problemas

### Claude no está aplicando el skill

**Solución:**
- Recuérdale explícitamente: "Usa el skill academic-task-planner"
- Vuelve a compartir el archivo SKILL.md en la conversación

### El PDF no se analiza correctamente

**Solución:**
- Verifica que el PDF sea legible (no imagen escaneada)
- Si falta información, Claude te preguntará - proporciona los datos faltantes

### Las fechas no tienen sentido

**Solución:**
- Revisa que las fechas en el PDF sean correctas
- Puedes pedirle a Claude que ajuste desde la fecha actual

### Quiero más o menos tareas

**Solución:**
- Pide a Claude: "Reduce/aumenta el número de tareas manteniendo lo esencial"
- O modifica la sección "Task Quantity Guidelines" en el SKILL.md

---

## 📞 Soporte

Si tienes problemas o sugerencias:
- Revisa que estés usando la última versión del skill
- Describe claramente el problema a Claude
- Proporciona el PDF que causa problemas (si aplica)

---

## 📝 Changelog

### Versión 2.0 (Octubre 2025)
- ✅ **NUEVO:** Pregunta cuándo vas a iniciar (no asume fecha oficial)
- ✅ **NUEVO:** Asigna tareas SOLO a días laborables (lunes-viernes)
- ✅ **NUEVO:** Respeta fines de semana automáticamente
- ✅ **NUEVO:** Excepción para fechas límite críticas (foro/entrega)
- ✅ **NUEVO:** Marca con ⚠️ las fechas límite en fin de semana
- ✅ Cálculo mejorado de días disponibles (solo laborables)

### Versión 1.0 (Octubre 2025)
- ✅ Creación inicial del skill
- ✅ Análisis automático de PDFs
- ✅ Cálculo de fechas de foro (3 días antes)
- ✅ Generación de IDs únicos
- ✅ Tags personalizados
- ✅ Organización por fases
- ✅ Checklist de verificación final

---

## 📄 Licencia

Este skill es de uso libre. Puedes modificarlo, compartirlo y adaptarlo a tus necesidades.

---

**¡Disfruta de tu nueva herramienta de planificación académica! 🎓✨**
