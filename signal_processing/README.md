# Signal Processing

> wave speed = wave length * frequency

## Low-pass filter

Low-pass filter provide a smoother form of a signal, removing the short-term fluctuations and leacving the longer-term trend.

### Ripple

Ripples are the fluctuations (measured in dB) in the pass band, or stop band, of a filter’s frequency magnitude response curve.

## Fourier Transform vs Laplace Transform vs Z-transform
- A laplace transform are for converting/representing a time-varying function in the "integral domain". It  transforms a signal to a complex plane s.
- Z-transforms are very similar to laplace but are discrete time-interval conversions, closer for digital implementations
- Fourier transforms are for converting/representing a time-varying function in the frequency domain. It transforms the same signal into the jw plane (is a special case of Laplace transform where the real part is 0. In Laplace domain, s=r+jw where r is the real part and the imaginary part depicts the oscillatory component)