# Modulation

## Baseband signal vs Carrier signal
- A baseband signal is one which has spectrum from 0 Hz to some fc Hz where fc is the cut off frequency (necessary to have spectrum around 0Hz to qualify for baseband signals). 
    - It suits short distance communication (usually in wired transmission)
- A carrier signal(typically sinusoidal, in some digital schemes pulses are also used) is one which has no such restriction on spectrum. 
    - It is a waveform that is modulated (modified) with an information-bearing signal for the purpose of conveying information.
    - However the carrier itself is not useful in transmitting the information, so the energy in the carrier component is a waste of transmitter power. Therefore, in many modern modulation methods, the carrier is not transmitted.

## Sideband

A sideband is a band of frequencies higher than or lower than the carrier frequency, that are the result of the modulation process

### Subcarrier

A subcarrier is a sideband of a radio frequency carrier wave, which is modulated to send additional information.

## Envelope

The envelope of an oscillating signal is a smooth curve outlining its extremes. The envelope thus generalizes the concept of a constant amplitude into an instantaneous amplitude.

### Envelope detector

Any AM or FM signal {\displaystyle x(t)}x(t) can be written in the following form
> <img src="https://latex.codecogs.com/gif.latex?\displaystyle x(t)=R(t)\cos(\omega t+\varphi (t))\">
In the case of AM, the phase component of the signal is constant and can be ignored. In AM, the carrier frequency is also constant. Thus, all the information in the AM signal is in R(t). R(t) is called the envelope of the signal. Hence an AM signal is given by the function
> <img src="https://latex.codecogs.com/gif.latex?\displaystyle x(t)=(C+m(t))\cos(\omega t)\">
with m(t) representing the original audio frequency message, C the carrier amplitude and R(t) equal to C + m(t). So, if the envelope of the AM signal can be extracted, the original message can be recovered.

## Spread specturm

Spread spectrum generally makes use of a sequential noise-like signal structure to spread the normally narrowband information signal over a relatively wideband (radio) band of frequencies.

### DSSS (Direct Sequence Spread Spectrum)

DSSS utilizes pseudo noise to modify the phase of the signal. This results in an output that closely resembles static noise and would appear as just that to others. But with a process called “de-spreading,” the original signal can be extracted from the noise as long as the pseudo-random sequence is known. A timing search algorithm needs to be employed for the receiver to correctly establish synchronization. **Interference between users is suppressed.**

### FHSS (Frequency-hopping spread spectrum)

A method of transmitting radio signals by rapidly changing the carrier frequency among many distinct frequencies occupying a large spectral band. The changes are controlled by a code known to both transmitter and receiver. FHSS is used to avoid interference, to prevent eavesdropping, and to enable code-division multiple access (CDMA) communications.

### FHSS vs DSSS:

- FHSS: utilizes frequency hopping. FHSS is easier to synchronize than DSSS. 
- DSSS: utilizes pseudo noise to modify the phase of the signal. DSSS is used in positioning systems while FHSS is not.

### Time-hopping

To achieve low probability of intercept (LPI), the transmission time is changed randomly by varying the period and duty cycle of the pulse (carrier) using a pseudo-random sequence. The transmitted signal will then have intermittent start and stop times.

### Chirp spread spectrum

A spread spectrum technique that uses wideband linear frequency modulated chirp pulses to encode information. A chirp is a sinusoidal signal whose frequency increases or decreases over time (often with a polynomial expression for the relationship between time and frequency).
- it uses its entire allocated bandwidth to broadcast a signal, making it robust to channel noise
- resistant to multi-path fading even when operating at very low power
- resistant to the Doppler effect
- it does not add any pseudo-random elements to the signal to help distinguish it from noise on the channel, instead relying on the linear nature of the chirp pulse.


## Analog carrier

### Analog data

- AM: Carrier amplitude
- FM: Carrier frequency
- PM: Carrier phase

### Digital data

- ASK: Carrier amplitude
- FSK: Carrier frequency
- PSK: Carrier phase
- QAM: Carrier amplitude & phase
    - It conveys two analog message signals, or two digital bit streams, by changing (modulating) the amplitudes of two carrier waves, using the amplitude-shift keying (ASK) digital modulation scheme or amplitude modulation (AM) analog modulation scheme. The two carrier waves of the same frequency are out of phase with each other by 90°, a condition known as orthogonality or quadrature. 
    - At the receiver, the two waves can be coherently separated (demodulated) because of their orthogonality property. 
    - Another key property is that the modulations are low-frequency/low-bandwidth waveforms compared to the carrier frequency, which is known as the narrowband assumption.

## Digital carrier

### Analog data

- PAM: Pulse amplitude
- PWM: Pulse width
- PM: Pulse position

### Digital data

- PCM: Pulse coding