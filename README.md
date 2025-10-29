# 📚 Claude Code Skills - Repositorio Personal

[![Skills](https://img.shields.io/badge/skills-1-blue)](https://github.com/TU-USUARIO/claude-code-skills)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-success)](https://github.com/TU-USUARIO/claude-code-skills)

Colección de skills personalizados para Claude Code y Claude.ai que automatizan tareas comunes y mejoran la productividad.

---

## 🎯 ¿Qué son los Skills?

Los **skills** son archivos markdown especializados que enseñan a Claude cómo realizar tareas específicas de manera consistente y profesional. Funcionan como "instrucciones expertas" que Claude lee y aplica cuando las necesita.

---

## 📦 Skills Disponibles

### 1. Academic Task Planner
**Versión:** 2.0 | **Estado:** ✅ Activo

Convierte guías de aprendizaje en PDF en checklists organizados con fechas, IDs únicos y tags personalizados.

**Características:**
- ✅ Pregunta cuándo vas a iniciar
- ✅ Asigna tareas solo a días laborables (L-V)
- ✅ Respeta fines de semana
- ✅ Cálculo automático de fecha límite de foro (3 días antes)
- ✅ IDs únicos para cada tarea
- ✅ Tags personalizados

**Links:**
- 📄 [Documentación completa](skills/academic-task-planner/README.md)
- 🚀 [Inicio rápido](skills/academic-task-planner/QUICKSTART.md)
- 💾 [Descargar SKILL.md](skills/academic-task-planner/SKILL.md)
- 🔗 [URL Raw](https://raw.githubusercontent.com/TU-USUARIO/claude-code-skills/main/skills/academic-task-planner/SKILL.md)

**Ejemplo de uso:**
```
[Sube SKILL.md a Claude]
"Usa el academic-task-planner con este PDF de tarea"
```

---

## 🚀 Instalación Rápida

### Método 1: Descarga Directa (Recomendado)

1. **Copia la URL raw del skill:**
   ```
   https://raw.githubusercontent.com/TU-USUARIO/claude-code-skills/main/skills/academic-task-planner/SKILL.md
   ```

2. **En tu conversación con Claude:**
   ```
   Lee este skill desde GitHub y aplícalo cuando suba PDFs académicos:
   [pega la URL]
   ```

### Método 2: Clonar el Repositorio

```bash
# Clonar todo el repositorio
git clone https://github.com/TU-USUARIO/claude-code-skills.git

# Navegar a un skill específico
cd claude-code-skills/skills/academic-task-planner

# Subir SKILL.md a Claude
```

### Método 3: Script de Instalación

```bash
# Descargar el script
curl -O https://raw.githubusercontent.com/TU-USUARIO/claude-code-skills/main/install.sh
chmod +x install.sh

# Instalar un skill
./install.sh academic-task-planner

# El skill se guarda en ~/.claude-skills/
```

---

## 📖 Cómo Usar un Skill

### Paso 1: Obtener el Skill
Descarga o accede al archivo `SKILL.md` del skill que quieres usar.

### Paso 2: Compartir con Claude
**Opción A - Claude.ai:**
- Sube el archivo `SKILL.md` en tu conversación
- Dile a Claude: "Lee este skill y aplícalo cuando sea relevante"

**Opción B - URL directa:**
- Comparte la URL raw con Claude
- Claude puede leerla directamente

### Paso 3: Usar
Una vez que Claude conoce el skill, úsalo:
```
Usa el [nombre-del-skill] con [tu contenido]
```

**Ejemplo:**
```
Usa el academic-task-planner con este PDF
```

---

## 📂 Estructura del Repositorio

```
claude-code-skills/
├── README.md                    # Este archivo
├── LICENSE                      # Licencia MIT
├── install.sh                   # Script de instalación
│
├── skills/                      # Todos los skills
│   └── academic-task-planner/   # Skill individual
│       ├── SKILL.md             # Archivo principal del skill
│       ├── README.md            # Documentación
│       ├── QUICKSTART.md        # Guía rápida
│       └── examples/            # Ejemplos
│
├── docs/                        # Documentación general
│   ├── installation.md
│   ├── usage.md
│   └── creating-skills.md
│
└── templates/                   # Plantillas
    └── skill-template.md
```

---

## 🛠️ Crear tu Propio Skill

¿Quieres crear un skill personalizado?

1. **Usa la plantilla:**
   ```bash
   cp templates/skill-template.md skills/mi-nuevo-skill/SKILL.md
   ```

2. **Edita el skill** con tu lógica y proceso

3. **Documenta:**
   - Crea un README.md explicando qué hace
   - Agrega ejemplos de uso
   - Include QUICKSTART.md

4. **Prueba** con Claude antes de compartir

5. **Sube** al repositorio:
   ```bash
   git add skills/mi-nuevo-skill/
   git commit -m "Add mi-nuevo-skill v1.0"
   git push
   ```

📚 **Guía completa:** [docs/creating-skills.md](docs/creating-skills.md)

---

## 📋 Lista de Skills Planeados

- [ ] **PDF Form Filler** - Llenar formularios PDF automáticamente
- [ ] **Research Summarizer** - Resumir papers académicos
- [ ] **Code Documenter** - Documentar código automáticamente
- [ ] **Meeting Notes** - Convertir transcripciones en notas estructuradas
- [ ] **Email Responder** - Generar respuestas profesionales a emails

¿Tienes ideas? [Abre un Issue](https://github.com/TU-USUARIO/claude-code-skills/issues)

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas!

1. Fork este repositorio
2. Crea una rama: `git checkout -b mi-nuevo-skill`
3. Haz tus cambios
4. Commit: `git commit -m "Add mi-nuevo-skill"`
5. Push: `git push origin mi-nuevo-skill`
6. Abre un Pull Request

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Puedes usar, modificar y distribuir libremente estos skills.

Ver [LICENSE](LICENSE) para más detalles.

---

## 🌟 Agradecimientos

Gracias a la comunidad de Claude por compartir ideas y mejores prácticas para crear skills efectivos.

---

## 📞 Contacto

- **Issues:** [Reportar un problema](https://github.com/TU-USUARIO/claude-code-skills/issues)
- **Discussions:** [Hacer una pregunta](https://github.com/TU-USUARIO/claude-code-skills/discussions)
- **Email:** tu@email.com

---

## 📊 Estadísticas

- **Skills totales:** 1
- **Downloads:** [En construcción]
- **Última actualización:** Octubre 2025

---

## 🔗 Links Útiles

- [Documentación de Claude](https://docs.anthropic.com/)
- [Claude Code](https://docs.claude.com/en/docs/claude-code)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Guides](https://guides.github.com/)

---

**⭐ Si encuentras útil este repositorio, considera darle una estrella!**

![Claude](https://img.shields.io/badge/Claude-Sonnet%204.5-orange)
![Markdown](https://img.shields.io/badge/Markdown-100%25-blue)
![Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)
