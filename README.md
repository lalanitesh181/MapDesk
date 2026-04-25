# MapDesk

MapDesk is a desktop GIS and cartographic presentation application for working with raster and vector spatial data in both 2D and 3D views.

## What This Repository Contains

This repository is intended to contain:

- Project information and documentation
- License and contribution guidance
- Screenshots and release notes if you want to add them later

This repository does **not** need to contain the full installer file directly when the installer is large.

## Main Capabilities

- Import GeoTIFF/TIFF rasters and GeoJSON/Shapefile vectors
- Render maps in 2D and terrain in 3D
- Overlay raster and vector layers on terrain
- Control raster symbology and colour ramps
- Build cartographic layouts
- Export map outputs and analytical map reports

## How To Share The Installer

Your installer should usually be uploaded in **GitHub Releases**, not committed into the main repository files list.

Reason:
- GitHub normal file upload in a repo has a size limit
- Large `.exe` installer files can fail or make the repository heavy

## Recommended GitHub Setup

Put these files in the repository root:

- `.gitignore`
- `README.md`
- `LICENSE`
- `CONTRIBUTING.md`

Then publish your installer in:

- `Releases` -> `Create a new release` -> upload `MapDesk-Installer.exe`

## Suggested About Description

Desktop GIS application for 2D and 3D raster-vector map visualization, terrain presentation, layout design, and report export.
