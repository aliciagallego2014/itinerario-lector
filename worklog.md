---
Task ID: 1
Agent: Main Agent
Task: Construir aplicación Itinerario Lector 3º ESO

Work Log:
- Leído documento docx con el itinerario lector (11 unidades, 37 obras, 3 géneros)
- Búsqueda web para cada obra: autor, páginas, editorial, año, resumen
- Correcciones solicitadas por el usuario: edición ilustrada Mitología (Jim Tierney, Folioscopio, 356 págs), Percy Jackson obra completa, Autorretratos De Muro a Muro (cárcel de Dueñas)
- Creado archivo de datos src/lib/books-data.ts con las 37 obras
- Creado componente BookCard con flip 3D (front: placeholder portada, back: info completa)
- Creado componente GenreFilter y UnitFilter
- Creado página principal con grid responsivo (3-7 columnas), búsqueda, filtros y agrupación por UD
- Actualizado layout (lang="es", metadata)
- Añadidos estilos CSS custom scrollbar
- Lint limpio, servidor compilando sin errores

Stage Summary:
- Aplicación funcional en / con tarjetas flip para 37 obras
- Filtros por género (cómic/narrativa/poesía) y unidad (1-11)
- Búsqueda por título o autor
- Grid responsivo que muestra muchas tarjetas a la vez
- Portadas con placeholder 3:2 listo para imágenes reales
