The discovery and measurement of exoplanets (planets outside our solar system) rely primarily on **indirect methods** that observe the planet's effect on its host star.

---

## 🔭 Exoplanet Discovery Methods

The most successful discovery methods use the gravitational and light-blocking effects of the orbiting planet:

### 1. Radial Velocity Method (Doppler Spectroscopy)
* **Principle:** Both the star and the planet orbit a common center of mass (the barycenter). The gravitational tug from the planet causes the star to **"wobble"**. This stellar wobble is measured by observing the **Doppler shift** in the star's light.
    * As the star moves *toward* Earth, its light is **blueshifted** (wavelengths compressed).
    * As the star moves *away* from Earth, its light is **redshifted** (wavelengths stretched). 
* **Best for:** Massive planets orbiting close to their stars (maximizing the wobble).
* **Mass Measurement:** This method is crucial for mass determination, as the amplitude of the star's velocity wobble is directly related to the planet's minimum mass ($M_p \sin i$).

### 2. Transit Method (Transit Photometry)
* **Principle:** This method detects the **temporary dimming** of a star's brightness when an orbiting planet passes directly in front of it from our perspective (a "transit"). 
* **Best for:** Planets with orbits aligned edge-on to our line of sight.
* **Provides:**
    * The **planet's size (radius)**, calculated from the amount of light blocked (the depth of the dip).
    * The **orbital period**, from the time between dips.

### 3. Gravitational Microlensing
* **Principle:** This method uses **Einstein's theory of general relativity**. The gravity of a foreground star and its planet acts like a lens, temporarily magnifying the light of a more distant, background star as the foreground system passes in front of it.
    * The star causes a large, bright spike in the background star's light.
    * The presence of a planet is revealed by a **second, smaller spike** or a brief perturbation in the light curve.
* **Best for:** Distant exoplanets, including those far from their stars, or even rogue planets.
* **Provides:** Information on the planet's mass-to-star mass ratio.

### 4. Direct Imaging
* **Principle:** Directly observing the light emitted or reflected by the exoplanet itself. This is exceptionally difficult because the faint planet is typically overwhelmed by the immense glare of its host star. **Coronagraphs** are used to block the star's light.
* **Best for:** Young, hot, large planets that are widely separated from their stars.

---

## ⚖️ Measuring the Mass of an Exoplanet

The most precise and common way to measure an exoplanet's true mass often involves combining data from two methods:

### 1. Radial Velocity (Primary Mass Measurement)

As noted above, the radial velocity method measures $M_p \sin i$, which is the **minimum mass** of the planet.

* $M_p$: True mass of the planet
* $i$: The inclination (or tilt) of the planet's orbital plane relative to our line of sight.

The actual mass ($M_p$) can only be known if the inclination $i$ is known.

### 2. Combining Radial Velocity and Transit Methods

The **Transit Method** is the key to finding the planet's true mass because transits *only* occur when the orbital plane is nearly edge-on ($i \approx 90^\circ$). If a planet is observed by *both* methods:

* The **Transit Method** confirms that $i \approx 90^\circ$, meaning $\sin i \approx 1$.
* The $M_p \sin i$ measured by the **Radial Velocity Method** then essentially equals the **true mass** ($M_p$).

This combination is also vital for calculating the planet's **density** ($\rho$), since density is mass divided by volume. The Transit Method gives the radius (for volume, $V \propto R^3$) and the Radial Velocity Method gives the mass ($M$).

$$\rho = \frac{M_p}{V} = \frac{\text{True Mass}}{\frac{4}{3} \pi R^3}$$

Knowing the density helps determine whether the exoplanet is rocky (like Earth) or gaseous (like Jupiter).

---

Would you like to know more about a specific method, or perhaps which space missions use which techniques?
