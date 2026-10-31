# NEXUS LAB 0.3 — Research
## Nueva capacidad
Búsqueda real de metadatos bibliográficos a través del endpoint público Crossref REST API (`/works`). No requiere clave API ni cuenta. La versión muestra título, autores, año, revista, DOI, recuento de citas y resumen cuando el registro lo incluye.

## Publicación desde Android
1. Extrae este ZIP.
2. Entra en la carpeta `nexus_lab_v0_3`.
3. Abre el repositorio GitHub `nexus-lab`.
4. Sustituye el archivo `index.html` de la raíz por el nuevo `index.html`.
5. Pulsa Commit changes y espera a que GitHub Pages actualice la web.

## Limitaciones
- Esta versión consulta metadatos, no descarga ni analiza automáticamente artículos completos.
- Los resúmenes no están disponibles para todos los registros.
- El historial se guarda en el almacenamiento local del navegador.
- Si una red bloquea solicitudes entre sitios (CORS), hará falta un backend intermediario.
- La búsqueda está sujeta a los límites de uso de Crossref; evita automatizar consultas masivas.
