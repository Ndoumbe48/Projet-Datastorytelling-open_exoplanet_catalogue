# Exoplanet Data Storytelling

This project uses data visualization to explore the Open Exoplanet Catalogue. Through static and interactive graphics, we uncover the physical laws, hidden structures, and observational biases that shape our understanding of exoplanets.

## Project Structure

The storytelling is organized into four acts, each answering a specific question.

### Act I : Exploratory Visuals

What are the global trends in the exoplanet census?

- Mass vs Radius : A power law  separates rocky worlds from gas giants.
- Period vs Semi-major axis : Exoplanets follow Kepler’s third law , just like our Solar System.
- Stellar mass distribution : Most detected planets orbit Sun-like stars (observational bias).

### Act II : Hidden Structures

Do exoplanets naturally form families?

- Outlier removal : Local Outlier Factor (LOF) cleans the dataset.
- Optimal K selection : Elbow method + Silhouette score.
- K-Means clustering reveals three interpretable groups.

### Act III : Detection Biases

How do our instruments influence what we discover?

- Bar chart : Transit and Radial Velocity dominate.
- Temporal evolution : The Kepler mission triggered an explosion of transits after 2009.
- Mass‑Radius by method : Transit finds small planets; RV targets giants.

### Act IV : 3D Galactic Map

- Interactive 3D map built from celestial coordinates (RA, Dec, distance in parsecs).
- Color = detection method, size = planetary mass.
- Sun at the center as a reference point.

## Dataset

Source: Open Exoplanet Catalogue

Size: around 5,000 confirmed exoplanets + Solar System planets

Key columns: mass, radius, period, semi_major_axis, eccentricity, discovery_method, host_star_mass, host_star_temp, ra_string, dec_string, distance_pc

## Conclusion

Data storytelling transforms raw catalogues into scientific insights. This project shows that exoplanets are not a single population. They form natural families, follow universal laws, and are revealed through biased instruments. The 3D map reminds us that every new mission rewrites our cosmic atlas.

## Authors

Ndoumbé BAYO and Tania Admane - 2025/2026