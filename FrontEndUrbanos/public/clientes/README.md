# Logos de clientes

Los logos que aparecen en el carrusel de clientes (home y Quiénes somos).

## Estado actual

Verificado abriendo cada archivo, no por su nombre — los nombres estaban mal.

| Archivo                     | Contiene                                   | Fuente |
|------------------------------|---------------------------------------------|--------|
| `ani.png`                   | Agencia Nacional de Infraestructura        | — |
| `compensar.png`             | Compensar                                  | — |
| `geb.png`                   | Grupo Energía Bogotá                       | — |
| `minsalud.png`              | Ministerio de Salud y Protección Social    | — (el archivo se llamaba `invias.png`) |
| `sae.png`                   | Sociedad de Activos Especiales             | — (el archivo se llamaba `findeter.png`) |
| `cundinamarca.png`          | Gobernación de Cundinamarca                | — (el archivo se llamaba `ideam.png`) |
| `invias.png`                | INVÍAS                                     | Wikimedia Commons (`INVIAS_Colombia_logo.svg`) |
| `findeter.svg`              | FINDETER                                   | findeter.gov.co (header oficial) |
| `ideam.png`                 | IDEAM                                      | Wikimedia Commons (`Ideam_(Colombia)_logo.png`) |
| `epm.png`                   | EPM                                        | Wikimedia Commons (`Logo_EPM.svg`) — reemplaza una foto de stock |
| `isa.png`                   | ISA (Interconexión Eléctrica)              | Wikimedia Commons (`Logo Interconexión Eléctrica.png`) — reemplaza una foto de stock |
| `alcaldia-bogota.png`       | Escudo de Bogotá (Alcaldía Mayor)          | Wikimedia Commons (`Escudo_de_Armas_de_Bogota.svg`) — reemplaza una foto de stock |
| `ministerio-vivienda.png`   | Ministerio de Vivienda, Ciudad y Territorio | Wikimedia Commons (`Logo_Ministerio_de_Vivienda_Ciudad_y_Territorio_Colombia.svg`) |
| `fna.png`                   | Fondo Nacional del Ahorro                  | Wikimedia Commons (`Logo-fna.png`) |

Las fotos de stock que ocupaban `epm`, `isa`, `alcaldia-bogota` y
`gobernacion-cundinamarca` (manos, teclados, genéricas) ya se borraron.

## Cómo agregar uno

1. Guarda el archivo aquí con el nombre de la entidad (`invias.png`, `epm.png`…).
2. **Ábrelo y comprueba que es el logo correcto** antes de referenciarlo.
3. Añade la ruta al array `CLIENTES` de
   `src/features/public/institucional/components/ClientesCarrusel.tsx`.

Formato: PNG o SVG con fondo transparente o blanco, ancho ~300 px y alto
~120 px. Si el archivo no existe o falla la carga, la tarjeta cae de vuelta al
nombre en texto, sin romper la fila.
