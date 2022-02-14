# Cellular

## FDMA (Frequency Division Multiple Access)

FDMA is a type of channelization protocol. In this bandwidth is divided into various frequency bands. Each station is allocated with band to send data and that band is reserved for particular station for all the time. The frequency bands of different stations are separated by small band of unused frequency and that unused frequency bands are called as guard bands that prevents the interference of stations.

## TDMA (Time Division Multiple Access)

TDMA is the channelization protocol in which bandwidth of channel is divided into various stations on the time basis. There is a time slot given to each station, the station can transmit data during that time slot only. Each station must aware of its beginning of time slot and the location of the time slot. TDMA requires synchronization between different stations.

## CDMA (Code Division Multiple Access)

In CDMA, all the stations can transmit data simultaneously. It allows each station to transmit data over the entire frequency all the time. Multiple simultaneous transmissions are separated by unique code sequence. Each user is assigned with a unique code sequence. 

### Statistical multiplexing gain

> capacity needed = mean + 3 * std

## FDMA vs TDMA vs CDMA

- FDMA: The rate of data is low. Mode of data transfer is continuous signal.
- TDMA: The rate of data is medium. Mode of data transfer is signal in burts.
- CDMA: The rate of data is high. Mode of data transfer is digital signal.

## OFDM (Orthogonal Frequency Division Multiplexing)

OFDM divides a wide band into several narrow-band sub-carriers, each of which carries information. OFDMA allow each user to be scheduled on a subset of frequency-time slots.

## NOMA (Non-orthogonal multiple access)

In NOMA, each user operates in the same band and at the same time where they are distinguished by their power levels. NOMA uses superposition coding at the transmitter such that the successive interference cancellation (SIC) receiver can separate the users both in the uplink and in the downlink channels.