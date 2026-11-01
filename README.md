# MetKinetics ProcessSim

Biblioteca web de simuladores y talleres didácticos de MetKinetics. Este repositorio es una versión de revisión preparada para validación antes de publicarse en el sitio web.

## Estructura

- `index.html`: catálogo responsivo con búsqueda y filtros.
- `assets/metkinetics-azul.png`: logo de MetKinetics.
- `recursos/<proceso>/index.html`: experiencia integrada por proceso.

## Recursos incluidos

- Bombeo
- Chancado y molienda
- Correas transportadoras
- Lixiviación en pilas

## Pendientes antes de publicación

- Integrar Hidroclasificación.
- Consolidar Química de soluciones y eliminar sus dependencias externas.
- Muestreo: localizar o definir el simulador que corresponde al taller disponible.
- Hacer una revisión final de contenido, contraste, navegación móvil y rutas de despliegue.

El catálogo muestra estos estados de forma explícita y no enlaza recursos incompletos.

## Publicación

El proyecto es estático y no requiere compilación. La carpeta completa se puede servir desde una ruta o subdominio del sitio MetKinetics. Antes de publicarla, se deben validar las rutas relativas bajo la ruta final y enlazar el repositorio remoto acordado.

## Dependencias

El catálogo no carga bibliotecas, fuentes ni servicios externos. Los recursos integrados deben conservar esa condición antes de su publicación.
