# EarthHarmonics: The Earth Information Jukebox
**2026 NASA Space Apps Challenge** • Track: *The Earth Information Jukebox*  
**Team:** The Winners 2026 (Azare)  
**Live Application:** [https://jarferh-tech.github.io/EarthHarmonics-Jukebox/](https://jarferh-tech.github.io/EarthHarmonics-Jukebox/)

---

## Mission Overview
NASA’s Earth Information Center (EIC) produces stunning visualizations of our changing planet, but presenting Earth science through visualization alone limits accessibility for visually impaired individuals and auditory learners.

**EarthHarmonics** is a multi-sensory Earth science sonification engine and audio-visual player built directly in the browser using the Web Audio API. It translates temporal environmental changes into dynamic acoustic frequencies, timbre shifts, and rhythmic patterns in real time.

---

## 5 Verified NASA Earth Science Datasets
1. **Atmospheric Carbon Dioxide ($CO_2$) Concentrations (1980–2026):**  
   *Source: NOAA Mauna Loa Keeling Curve & NASA Orbiting Carbon Observatory-2 (OCO-2).*  
   *Sonification: Ascending pitch frequency from deep 130 Hz cello tones up to 880 Hz as $CO_2$ climbs from 338 ppm to over 426 ppm.*
2. **Global Surface Temperature Anomaly (1980–2026):**  
   *Source: NASA Goddard Institute for Space Studies (GISTEMP v4).*  
   *Sonification: Minor-to-augmented harmonic dissonance with modulated saw oscillators as temperatures warm by $+1.38^\circ\text{C}$.*
3. **Arctic Sea Ice Minimum Extent (1980–2026):**  
   *Source: NASA Cryosphere Science Research & National Snow and Ice Data Center (NSIDC).*  
   *Sonification: Bright, high-frequency crystalline chimes decaying into hollow, filtered sub-bass as summer sea ice shrinks.*
4. **Ocean Chlorophyll-a Biomass Index (1980–2026):**  
   *Source: NASA SeaWiFS & MODIS-Aqua Ocean Color Telemetry.*  
   *Sonification: Liquid, rolling arpeggiation reflecting marine phytoplankton primary productivity.*
5. **Global Wildfire Smoke Aerosol Optical Depth (1980–2026):**  
   *Source: NASA MODIS & VIIRS Terra/Aqua Aerosol Sensors.*  
   *Sonification: Filtered noise bursts and accelerating percussive rhythms during intense wildfire outbreaks.*

---

## Key Features & Accessibility
* **Live Web Audio API Polyphony:** Synthesizes sound directly in code with zero external audio samples or network latency.
* **Real-Time Oscilloscope & Spectrum Analyzer:** HTML5 Canvas FFT visualizer rendering time-domain waveforms and frequency bars.
* **3 Sound Themes:** Cosmic Poly-Synth, Oceanic Ambient, and Acoustic Chime / Marimba.
* **Screen Reader Accessibility:** Live auditory transcription logs translating exact frequencies ($Hz$) and scientific values into accessible text.
* **Zero Dependencies:** Pure vanilla HTML5, CSS3, and modern JavaScript.

---

## NASA Resources
* **NASA Earth Information Center (EIC):** [https://earth.gov/](https://earth.gov/)
* **NASA GISS Surface Temperature Analysis (GISTEMP v4):** [https://data.giss.nasa.gov/gistemp/](https://data.giss.nasa.gov/gistemp/)
* **NASA Orbiting Carbon Observatory (OCO-2):** [https://ocov2.jpl.nasa.gov/](https://ocov2.jpl.nasa.gov/)
* **NASA Ocean Color Science (MODIS-Aqua):** [https://oceancolor.gsfc.nasa.gov/](https://oceancolor.gsfc.nasa.gov/)

---

## License
Open source under the [MIT License](LICENSE).
