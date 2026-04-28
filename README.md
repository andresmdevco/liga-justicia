# ⚡ liga-justicia

> Repositorio de práctica · Curso de Git & GitHub en Udemy


Este repositorio fue utilizado como práctica durante un curso de Git y GitHub tomado en Udemy. El contexto temático es el universo de la Liga de la Justicia, usado para simular un proyecto colaborativo real mientras se aplican los conceptos del curso.

---

## Objetivos del repositorio

Este proyecto se encarga de manejar los planes de la liga de la justicia.


## 📚 Conceptos aprendidos

### Trabajo con el repositorio remoto
- **`git push`** — subir cambios locales al repositorio remoto
- **`git pull`** — bajar e integrar cambios del remoto al local
- **`git fetch`** — descargar cambios del remoto sin integrarlos automáticamente

### Estrategias de sincronización
- **`git pull --rebase`** — integrar cambios manteniendo un historial lineal
- **Pulling without reconcile strategy** — configurar el comportamiento por defecto del pull.
  Se trabajaron dos configuraciones en orden durante el curso:

```bash
  # 1. Primero: permitir pull solo si es fast-forward
  git config --global pull.ff only

  # 2. Luego: cambiar a rebase como estrategia por defecto
  git config --global pull.rebase true
```

  El segundo comando se aplicó entrando al archivo de configuración global directamente con:

```bash
  git config --global -e
```

### Etiquetas y releases
- Crear **release tags** para marcar versiones estables del proyecto
- **Push de tags** al repositorio remoto con `git push --tags`

### Clonación
- **`git clone`** — clonar un repositorio remoto para trabajar localmente

### Documentación
- Redacción de contenido con sintaxis **Markdown**
- Agregar **comentarios descriptivos en commits** para documentar el historial de cambios
