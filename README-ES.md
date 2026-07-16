# OWASP MASVS v2 Checklist

Una herramienta interactiva para realizar auditorías de seguridad en aplicaciones móviles siguiendo el estándar **OWASP Mobile Application Security Verification Standard (MASVS) v2.0** y el **MASTG v1.7.0**.

🔗 **[Abrir la herramienta →](https://llucloh.github.io/masvs-web-checklist/)**

---

## ¿Qué es esto?

Esta checklist cubre los 7 dominios de seguridad del MASVS v2 con todos sus controles y tests asociados del MASTG:

| Dominio | Descripción |
|---|---|
| MASVS-STORAGE | Almacenamiento seguro de datos |
| MASVS-CRYPTO | Criptografía aplicada correctamente |
| MASVS-AUTH | Autenticación y autorización |
| MASVS-NETWORK | Comunicaciones de red seguras |
| MASVS-PLATFORM | Interacción con la plataforma y WebViews |
| MASVS-CODE | Calidad de código y actualizaciones |
| MASVS-RESILIENCE | Anti-reversing y anti-tampering |

## Características

- **Sin instalación** — funciona directamente en el navegador
- **Progreso local** — los datos se guardan en `localStorage`, sin servidores
- **Android e iOS** — filtra tests por plataforma
- **Búsqueda** — encuentra tests por ID o nombre
- **Notas por control** — anota evidencias y hallazgos
- **Exportación** — descarga tu auditoría en JSON o Markdown
- **Impresión** — genera PDF desde el navegador
- **Múltiples proyectos** — guarda y carga diferentes auditorías

## Uso

1. Abre la herramienta en el link de arriba
2. Escribe el nombre de tu proyecto (aplicación auditada)
3. Ve marcando los tests a medida que los completas
4. Añade notas con evidencias en cada control
5. Exporta el resultado en Markdown para incluirlo en tu informe

> El progreso se guarda automáticamente en tu navegador. Cada alumno mantiene sus propios datos de forma independiente.

## Para instructores

Cada alumno trabaja con su propia copia local de los datos. No hay cuenta ni login necesario. Para entregar la auditoría, el alumno puede:

- Exportar el **JSON** (datos completos para revisar)
- Exportar el **Markdown** (formato legible para el informe)
- Hacer **Print → PDF** desde el navegador

## Estándar de referencia

- [OWASP MASVS v2.0.0](https://mas.owasp.org/MASVS/)
- [OWASP MASTG v1.7.0](https://mas.owasp.org/MASTG/)
- [mas.owasp.org](https://mas.owasp.org)

## Ejecutar localmente

No necesitas ningún servidor. Simplemente descarga el `index.html` y ábrelo en tu navegador:

```bash
git clone https://github.com/llucloh/masvs-checklist.git
cd masvs-checklist
open index.html   # macOS
# o doble clic en index.html en Windows/Linux
```

## Créditos

Herramienta desarrollada por **llucloh** para uso educativo en formaciones de seguridad móvil.

Basada en los estándares abiertos de [OWASP MAS](https://mas.owasp.org).
