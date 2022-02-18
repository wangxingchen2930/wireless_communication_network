# Path Loss in Wireless Channels

## Signal Propagation Factors

### Obstacles
- Reflection
    - part reflected back
    - part absorbed
    - part through second medium
- Diffraction
    - caused by sharp irregularities (edges)
    - less of effect for small wavelengths (higher frequency like mmWave)
- Scattering
    - wave travels consists of objects that are small compared to the wavelength, and where the number of obstacles per unit volume is large 
    - result is that the EM wave travels in all directions

### Mobility

As transmitting and receiving terminals move, the conditions of reception at either end change

### Multipath

Different resulting paths of the EM signals can enhance or cancel each other, depending on their amplitude/phase
- **Fading** refers to the fact that the received signal strength can fluctuate significantly over time and space

## Modeling approaches

### EM modeling

Maxwell’s equations for electromagnetism

### Ray-tracing

Using the geometry of the paths

### Probabilistic models (most practical)

Capture (at least) three components that affect the signal once it is transmitted:
- Path loss (attenuation of the signal)
- Shadow fading (large-scale fading/log-normal fading)
- Multi-path fading (small-scale fading)