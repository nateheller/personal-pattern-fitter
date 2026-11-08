# Personal Pattern Fitter

A local-first, open-source sewing pattern fitting application designed to help sewists adapt commercial PDF patterns to their individual body measurements.

## Project Goal

Make sewing pattern alterations more accessible, accurate, and repeatable.

Users should be able to import a sewing pattern PDF, select a saved body measurement profile, review recommended fitting adjustments, and export a customized printable pattern.

The application aims to preserve the original garment design, intended ease, seam relationships, and construction details.

## Planned Features

- Import vector-based PDF sewing patterns
- Reconstruct tiled PDF patterns
- Identify pattern pieces and available sizes
- Save and manage body measurement profiles
- Identify and confirm sewing landmarks
- Compare finished garment dimensions with body measurements
- Calculate and preview fitting alterations
- Validate seam compatibility and geometric consistency
- Export calibrated, printable PDF patterns
- Operate locally without requiring cloud AI services

## Technology

- **Python:** PDF processing, geometry, fitting calculations, and validation
- **PyMuPDF:** PDF inspection and vector extraction
- **Shapely:** Geometric operations
- **pytest:** Automated testing
- **React + TypeScript:** User interface
- **Desktop packaging:** To be determined

## Development Roadmap

### v0.1 — Pattern Importer and Analyzer

Import and display sewing patterns, identify pattern pieces, manage measurements, and establish verified garment dimensions.

### v0.2 — Fitting Engine

Calculate and preview pattern alterations while preserving intended ease and compatible sewing lines.

### v0.3 — Printable Pattern Generator

Generate calibrated, tiled PDF patterns suitable for home printing.

### v0.4 — Generalized Pattern Support

Expand compatibility across different sewing-pattern manufacturers, layouts, and garment types.

## Initial Validation Pattern

Development begins with Mood Fabrics MDF126 — Primrose Pants.

The original 40-tile PDF has been reconstructed into a registered vector master. Pattern landmark identification, finished garment measurements, fitting alterations, and physical fit validation remain in progress.

## Engineering Principles

- Local-first and privacy-conscious
- Deterministic, reproducible geometry
- Original pattern preservation
- Explicit measurement units and scale validation
- Human confirmation of uncertain pattern features
- Automated regression testing
- No mandatory AI dependency at runtime

## Project Status

Early development — initial application architecture and implementation.

## Licensing

MIT License (subject to repository setup).

Commercial sewing patterns used for testing remain the property of their respective copyright holders and are not included under this project's software license.
