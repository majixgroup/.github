# Cómo contribuir a `.github`

Este repositorio es la cara pública de `majixgroup` en GitHub y contiene
configuración de organización. Dos reglas, sin excepción:

1. **Solo Marcos (CEO) aprueba cambios aquí** — ver `CODEOWNERS`. Cualquier
   cambio pasa por Pull Request; `main` tiene branch protection real
   (revisión obligatoria + CODEOWNERS, sin force-push, sin borrado).
2. **Nada de documentación interna vive aquí.** El único contenido visible
   en el perfil público de la organización es `profile/README.md`. Lo demás
   (`CODEOWNERS`, plantillas de PR/issues, `SECURITY.md`) es configuración
   de organización, no contenido — no es el sitio para notas internas,
   arquitectura de acceso, ni nada que no deba ser público. Esa
   documentación vive en el repo privado
   [`docs`](https://github.com/majixgroup/docs), carpeta `github/`.

## Antes de proponer un cambio

Pregúntate: ¿esto es algo que cualquiera fuera de MAJIX debería poder ver
si abre este repositorio? Si la respuesta es no, no va aquí.
