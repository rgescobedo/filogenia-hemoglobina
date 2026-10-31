[🏠 Inicio](../README.md)

# 🧪 Formato del archivo FASTA

Tu base de datos es un archivo de texto plano (`.fasta`, `.fas` o `.txt`) con una entrada por organismo. Cada entrada tiene:

1. Una línea de **encabezado** que empieza con `>` seguido del nombre del organismo (sin espacios).
2. Una o varias líneas con la **secuencia** de nucleótidos (A, C, G, T).
3. Una línea en blanco antes de la siguiente entrada.

```text
>Homo_sapiens
ACGTACGTACGT...   ← aquí va la secuencia copiada de NCBI
ACGTACGTACGT...

>Canis_lupus_familiaris
ACGTACGTACGT...

>Danio_rerio
ACGTACGTACGT...
```

> [!NOTE]
> Las letras de arriba solo ilustran el formato; no son secuencias reales. **Cada estudiante descarga sus propias secuencias** desde [NCBI Nucleotide](https://www.ncbi.nlm.nih.gov/nuccore/) siguiendo la [Parte 2](../docs/02_base_de_datos_ncbi.md).

## ✅ Lista de verificación antes de abrir en SeaView

- [ ] Cada encabezado empieza con `>`
- [ ] Los nombres no tienen espacios, acentos ni paréntesis
- [ ] No hay nombres repetidos
- [ ] Todas las secuencias son de *HBA1* (no *HBB*, *HBA2* ni *AHSP*)
- [ ] Las longitudes son parecidas (cientos de pb, no miles)
- [ ] Incluiste al menos un pez como grupo externo
- [ ] El archivo está guardado como texto plano (no `.docx`)
