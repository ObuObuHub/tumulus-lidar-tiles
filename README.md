# tumulus-lidar-tiles

ANCPI LAKI III DTM 0.5 m tiles for **Dolj county, Romania**, redistributed **unmodified**, so that the
[tumulus-lidar-detector](https://github.com/ObuObuHub/tumulus-lidar-detector) Colab demo works while ANCPI's
geoportal is offline.

- **Source:** ANCPI (Agenția Națională de Cadastru și Publicitate Imobiliară), LAKI III, DTM 0.5 m. **© ANCPI.**
- **Files:** the original zips (ASCII grid), 1 × 1 km each, named `N_E.zip` with N, E in km (EPSG:3844, Stereo 70).
- **Layout:** 8,988 tiles in releases `dolj-01` … `dolj-09` (at most 1,000 files per release); `index.json` in
  release `index` maps each tile to its release.
