# 🛰️ ST3LLA - Cartografía de Rutas & Ecosistema Jacobeo

<p align="left">
  <a href="https://jreyes13.github.io/st3lla/"><img src="https://img.shields.io/badge/🌐_ST3LLA_Live_Map-jreyes13.github.io%2Fst3lla-2A9D8F?style=for-the-badge&logo=leaflet&logoColor=white" alt="ST3LLA Live Map" /></a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Project-ST3LLA-1D3557?style=flat-square&logo=compass&logoColor=white" alt="Project ST3LLA" />
  <img src="https://img.shields.io/badge/Ecosystem-TRISAT%20%7C%20WINE%C2%B3ai-F4A261?style=flat-square" alt="TRISAT & WINE³ai" />
  <img src="https://img.shields.io/badge/Focus-Galicia%20%7C%20Mar%20%26%20Terra-264653?style=flat-square" alt="Galicia Mar & Terra" />
  <img src="https://img.shields.io/badge/Coverage-24%2C493%20km-orange?style=flat-square" alt="24,493 km covered" />
  <img src="https://img.shields.io/badge/Tracks-223%20GPX-success?style=flat-square" alt="223 GPX tracks" />
  <img src="https://img.shields.io/badge/QGIS-3.x-589632?style=flat-square&logo=qgis&logoColor=white" alt="QGIS 3.x" />
  <img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=flat-square" alt="GPL-3.0 License" />
</p>

**ST3LLA** (*Campus Stellae*) es la plataforma cartográfica integral de rutas que fusiona la teledetección espacial de **TRISAT**, el conocimiento de la tierra y del vino impulsado por IA de **WINE³ai**, y la mayor red de senderos culturales y de peregrinación, comenzando por el mítico **Camino de Santiago**.

Con epicentro en **Galicia** —donde el océano Atlántico y la tierra firme se abrazan como confluencia histórica de personas y culturas—, **ST3LLA** triangula:
1. **El Cielo (Espacio & TRISAT):** Datos de observación satelital, posicionamiento GNSS y monitorización medioambiental.
2. **La Tierra & El Vino (WINE³ai):** Terruño, paisajes vitivinícolas protegidos, senderos y patrimonio etnográfico.
3. **El Mar & Las Personas (ST3LLA):** Rutas costeras e interiores, mapas interactivos y el espíritu de encuentro humano del peregrino.

---

## 📊 Global Route Catalog Summary

| Code | Route / Camino | Stages & Tracks | Distance (km) | Format |
| :--- | :--- | :---: | :---: | :---: |
| **ES01** | Camino Francés | 32 | 809.8 km | GPX |
| **ES02** | Camino Aragonés (Somport – Puente la Reina) | 1 | 71.8 km | GPX |
| **ES03** | Camino del Norte (Irún – Santiago, 34 etapas limpias) | 34 | 747.1 km | GPX |
| **ES04** | Camino Primitivo (Oviedo – Santiago) | 1 | 303.5 km | GPX |
| **ES07** | Vía de la Plata (Sevilla – Astorga, 3 tramos) | 3 | 680.0 km | GPX |
| **ES08** | Camino Sanabrés (Granja de Moreruela – Santiago) | 2 | 419.9 km | GPX |
| **ES09** | Camino Portugués Central (Galicia) | 18 | 91.4 km | GPX / KML |
| **ES10** | Camino Portugués de la Costa (Galicia) | 10 | 78.1 km | GPX / KML |
| **ES11** | Camino Inglés (Ferrol – Santiago) | 1 | 156.7 km | GPX |
| **ES12** | Camino de Madrid (Madrid – Sahagún) | 24 | 409.8 km | GPX / KML |
| **ES13** | Camino de Fisterra y Muxía | 1 | 149.2 km | GPX |
| **ES14** | Camino de Invierno (Ponferrada – Santiago) | 1 | 223.4 km | GPX |
| **ES15** | Camino Mozárabe (Andalucía – Mérida) | 1 | 427.8 km | GPX |
| **ES16** | Camino de Levante (Valencia – Zamora) | 1 | 361.0 km | GPX |
| **ES19** | Camino del Sureste (Alicante – Benavente) | 1 | 891.3 km | GPX |
| **ES21** | Camino Olvidado (Bilbao – Villafranca del Bierzo) | 1 | 481.0 km | GPX |
| **EU-PT** | Camino Portugués en Portugal (Lisboa – Oporto – Valença) | 1 | 382.8 km | GPX |
| **EU-FR** | Rutas Francesas (*Voies de Saint-Jacques*: Podiensis, Lemovicensis, Turonensis, Tolosana, Piémont) | 5 | 4,657.2 km | GPX |
| **EU-CZ** | Rutas Jacobeas Checas & Praga–Santiago | 9 | 3,006.5 km | GPX / KML |
| **EU-DE** | Rutas Alemanas (*Jakobsweg*) | 76 | 10,145.1 km | GPX / KML |
| **TOTAL** | **Red Jacobea Integrada** | **223** | **24,493.1 km** | **GPX** |

---

## 🗺️ Interactive Web Viewer

👉 **Acceso directo online:** **[https://jreyes13.github.io/st3lla/](https://jreyes13.github.io/st3lla/)**

También puedes abrir directamente [`index.html`](index.html) de manera local en cualquier navegador:
- **Panel lateral redimensionable y deslizable**:
  - Arrastra el divisor lateral para ampliar o reducir el ancho del panel según tus necesidades.
  - Botón flotante para ocultar/mostrar el panel y navegar el mapa a pantalla completa.
  - Filtros rápidos por región (🇪🇸 Principales, 🇪🇸 Enlaces, 🇵🇹 Portugal, 🇫🇷 Francia, 🇩🇪🇨🇿 Europa).
- **Control individual de capas**:
  - Botón de centrado rápido (*zoom*) por ruta individual.
  - Botón de encendido/apagado (*ojo*) para mostrar u ocultar caminos específicos en el mapa.
- **Topología continua sin saltos**: Algoritmo de segmentación inteligente que evita líneas rectas transversales sobre vacíos cartográficos.
- **Base Layers 100% libres de API Keys**: OpenStreetMap, IGN Topográfico Nacional (MTN), Ortofoto PNOA (IGN), OpenTopoMap (Relieve), Esri Satélite.
- **Búsqueda & Filtrado en tiempo real**: Búsqueda instantánea con botón de limpieza por código, nombre o etapa.
- **Altitudes & Estadísticas**: Métricas de elevación acumulada ($+$ y $-$), distancias continuas y descarga directa en 1 clic de cada archivo `.gpx`.

---

## 📌 Project Objectives

- **Geospatial Centralization**: Bring together detailed stages, trails, and variants of Jacobean routes, linking both the core trails in Spain and broader European feeder ways (Germany, Czech Republic).
- **Cartography & GIS with QGIS**: Maintain organized QGIS projects (`.qgz`) for visualization, topological validation, digital elevation model (DEM) analysis, and map generation.
- **Interoperability**: Provide clean tracks in standard formats (`.gpx`, `.kml`, and `.geojson`) suitable for GPS units, mobile apps (Komoot, Wikiloc, OsmAnd, Google Earth), and web-based map viewers.

---

## 📁 Repository Structure

```text
.
├── GPX/
│   ├── 01-Camino_Frances/                # Camino Francés (Stages 1 through 33) [.gpx]
│   ├── ES02-Camino-Aragones/             # Camino Aragonés [.gpx]
│   ├── ES03-Camino-del-Norte/            # Camino del Norte (34 etapas + completo) [.gpx]
│   ├── ES04-Camino-Primitivo/            # Camino Primitivo completo [.gpx]
│   ├── ES07-Via-de-la-Plata/             # Vía de la Plata (Sevilla, Mérida, Salamanca, Astorga) [.gpx]
│   ├── ES08-Camino-Sanabres/             # Camino Sanabrés (Granja, Ourense, Santiago) [.gpx]
│   ├── ES09-Camino-Portugues-Central/    # Camino Portugués Central [.gpx]
│   ├── ES10-Camino-Portugues-de-la-Costa/# Camino Portugués de la Costa [.gpx]
│   ├── ES11-Camino-Ingles/               # Camino Inglés completo [.gpx]
│   ├── ES12-Camino-de-Madrid/            # Camino de Madrid stages & variants [.gpx & .kml]
│   ├── ES13-Camino-Fisterra-Muxia/       # Camino de Fisterra y Muxía [.gpx]
│   ├── ES14-Camino-de-Invierno/          # Camino de Invierno [.gpx]
│   ├── ES15-Camino-Mozarabe/             # Camino Mozárabe [.gpx]
│   ├── EU/                               # European Jacobean trails
│   │   ├── CZ/                           # Czech Republic routes (Žitavská, Všerubská, etc.) [.gpx & .kml]
│   │   └── DE/                           # German Jakobsweg network (Via Baltica, Regia, etc.) [.gpx & .kml]
│   ├── GoogleMaps_Praga_Santiago.gpx     # Trans-European route connecting Prague to Santiago
│   └── 170615-camino-santiago-en-rep-checa-praga-radotin.gpx
├── QGIS/
│   ├── CaminoSantiago.qgz                # Primary QGIS map project (repaired & validated)
│   └── CaminoSantiago_OLD.qgz            # Legacy QGIS map project
├── data/
│   ├── routes_catalog.json               # Aggregated geospatial metadata (distances, elevations)
│   ├── routes.geojson                    # Full vector network for web mapping
│   └── routes_geojson.js                 # Standalone loader for local file viewing
├── scripts/
│   ├── kml_to_gpx.py                     # Lossless KML -> GPX 1.1 converter
│   ├── import_open_pilgrimages.py        # Importer for stage-breakdown routes
│   ├── fetch_osm_camino.py               # OSM relation API fetcher & track assembler
│   └── generate_catalog.py               # Route parser, metrics calculator & GeoJSON builder
├── index.html                            # Interactive Leaflet web map viewer
├── LICENSE                               # GPL-3.0 License
└── README.md                             # Repository documentation
```

---

## 🛠️ Tooling & Scripts

### 1. Convert KML to GPX
```bash
python3 scripts/kml_to_gpx.py <file.kml o directorio>
```

### 2. Recalculate Catalog & GeoJSON
```bash
python3 scripts/generate_catalog.py
```

### 3. Fetch Official OSM Camino Relations
```bash
python3 scripts/fetch_osm_camino.py
```

---

## 🗺️ Sources & Official Cartographic References

The geospatial data and routes are referenced against and verified with official mapping agencies and recognized pilgrim federations:

- **[IGN - National Geographic Information Infrastructure](https://nco.ign.es/Caminosantiago/)**: Official interactive map of Jacobean routes across Spain provided by the National Geographic Institute of Spain (*IGN*).
- **[CNIG Download Center](https://centrodedescargas.cnig.es/CentroDescargas/mapas-camino-santiago)**: Official digital cartography, aerial photography (PNOA), digital elevation models (DEM), and vector datasets of the Camino de Santiago.
- **[FEAACS - Spanish Federation of Associations of Friends of the Camino de Santiago](https://www.caminosantiago.org/)**: Historical routes, stage itineraries, official variants, and hostel networks.
- **[OpenStreetMap & Open Pilgrimages](https://www.openstreetmap.org/)**: Community-verified collaborative cartography and high-precision GPS trace alignments.
