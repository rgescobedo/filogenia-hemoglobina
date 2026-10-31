[🏠 Inicio](../README.md)

# 👩‍🏫 Notas para el docente

## Planeación sugerida

| Momento | Actividad | Tiempo aprox. |
| --- | --- | --- |
| Antes de clase | Ver la película y armar la tabla de organismos; instalar SeaView | Tarea |
| Sesión 1 | Búsqueda en NCBI y construcción del FASTA (Partes 1–2) | 1.5–2 h |
| Sesión 2 | Alineamiento, recorte y lanzamiento de PhyML (Partes 3–4) | 1.5 h |
| Fuera de clase | Terminar el bootstrap, enraizar, exportar y redactar el reporte | 1 semana |

## Errores frecuentes

| Síntoma | Causa probable | Solución |
| --- | --- | --- |
| SeaView no reconoce el archivo | Falta el `>` o se guardó como `.docx`/`.rtf` | Guardar como texto plano y revisar encabezados |
| Un mamífero se agrupa con aves o peces | Se descargó *HBB*, *HBA2* o *AHSP* | Verificar el nombre completo del registro en NCBI |
| Una secuencia mide miles de pb | Es un fragmento genómico o cromosoma | Elegir un registro de ARNm (*mRNA*) o CDS |
| Nombres cortados o repetidos en el árbol | Espacios o nombres duplicados en el FASTA | Usar `Genero_especie` únicamente |
| El árbol no tiene sentido biológico | Se borraron nucleótidos del centro del alineamiento | Volver a cargar el FASTA original y recortar solo extremos |
| PhyML tarda demasiado | Muchas secuencias o equipo lento | Reducir a 500 réplicas con evidencia (captura a las 24 h) |
| No se puede enraizar correctamente | No se incluyó un pez | Agregar una secuencia de pez (p. ej. *Danio rerio*) |

## Resultado esperado

Con un buen muestreo, el árbol enraizado con el pez debería recuperar en general los grandes grupos de vertebrados: **mamíferos** separados de **aves y reptiles**, y dentro de los mamíferos agrupaciones como primates, carnívoros y cetáceos. Un solo gen no siempre recupera la filogenia de especies completa; las discrepancias son una buena oportunidad para discutir las preguntas 4, 6 y 10 del reporte.

## Rúbrica sugerida

| Criterio | Peso |
| --- | :---: |
| Introducción propia (≥ 1 cuartilla, con referencias) | 15 % |
| Tabla de organismos completa y nombres científicos correctos | 15 % |
| Base de datos con el gen correcto (*HBA1*) | 15 % |
| Árbol enraizado con valores de bootstrap y pie de figura | 20 % |
| Respuestas a las preguntas | 20 % |
| Conclusión | 10 % |
| Formato y referencias | 5 % |

> Ajusta los pesos según los criterios de evaluación de tu curso.
