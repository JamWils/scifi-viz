# Sci-Fi FUI Visualization

This repository is for experimenting with Sci-Fi FUI (Fantasy User Interface) visualization.

## Git LFS

This repository uses Git LFS to manage large asset files. The following file types are tracked:

- **Houdini files**: `.hip`, `.hiplc`, `.hipnc`, `.hda`, `.otl`
- **Geometry**: `.bgeo`, `.bgeo.sc`, `.vdb`, `.abc`, `.fbx`, `.obj`
- **USD**: `.usd`, `.usda`, `.usdc`
- **Images**: `.exr`, `.tif`, `.tiff`, `.tx`, `.rat`, `.pic`, `.psd`
- **Video**: `.mp4`, `.mov`, `.avi`
- **Datasets**: CSV files in the `datasets/` folder

## Satellite Data Definitions

### Orbit Classes

- **LEO (Low Earth Orbit)**: Orbits between ~160-2,000 km altitude. Used for Earth observation, communications, and the ISS. Typical period: 90-120 minutes.
- **MEO (Medium Earth Orbit)**: Orbits between ~2,000-35,786 km altitude. Used for navigation systems like GPS, GLONASS, and Galileo. Typical period: 2-12 hours.
- **GEO (Geostationary Orbit)**: Circular orbit at ~35,786 km altitude above the equator. Satellites appear stationary relative to Earth. Period: exactly 24 hours (1,436 minutes).

### Orbital Parameters

- **Inclination**: The angle between the orbital plane and Earth's equator, measured in degrees (0° to 180°). 0° is equatorial, 90° is polar, >90° is retrograde.
- **Period**: The time it takes for a satellite to complete one full orbit around Earth, measured in minutes.
