#  Pokédex Nacional - Práctica 1 PMDM

Aplicación Android nativa desarrollada en **Java** y **XML** para el módulo de Programación Multimedia y Dispositivos Móviles (Temas 1, 2 y 3). 

##  Descripción
**Pokédex Nacional** es una interfaz de consulta enciclopédica de Pokémon que muestra la ficha técnica de cada criatura ordenada por su número de registro, su forma actual, el primer videojuego en el que debutó y las distintas descripciones de la Pokédex a lo largo de las ediciones.

El proyecto destaca por una gestión estricta de recursos en `res/`:
- **0% Hardcoded:** Textos, colores y dimensiones (`dp`/`sp`) centralizados en `res/values/`.
- **Internacionalización completa:** Soporte nativo para Español (`values/`) e Inglés (`values-en/`).
- **Recursos gráficos optimizados:** Combinación de *Vector Assets* para iconografía e imágenes de mapa de bits (`.png`) para ilustraciones, junto con un icono adaptativo personalizado en `mipmap`.
- **Estilos reutilizables:** Tema personalizado y estilos propios aplicados a títulos, tarjetas de texto y botones.

##  Cómo ejecutar el proyecto
1. Clona este repositorio en tu equipo:
   ```bash
   git clone [https://github.com/TU_USUARIO/PMDM_P1_MiguelAngelToroChaves.git](https://github.com/TU_USUARIO/PMDM_P1_MiguelAngelToroChaves.git)
