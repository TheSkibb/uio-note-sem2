# Optical Networking

Guest Lecture: from tampnet

## Why fiber optics instead of wireless

- bigger bandwidt
- less interference

## Where is fiber optics used

- Transport
- Access networks
    - home
    - business
- Mobile base stations and antennas
- Inside datacenters
    - patching between server and storage

> *Optical is becoming more and more visible. Previously it was used more "behind the scenes", but is increasingly becoming visible to end users*

## Propagation through fibre

- Fibre is a thin glass string
- light pulses are reflected in the core
- shallow angle => approximately 0 loss (different from copper)
- bending the cable too much => light escapes the fibre

## capacity in different media

- Fibre                          50 Tb/s
- Copper twisted pair           100 Mb/s
- Line of sight (microwave)      10 Gb/s
- Satelite                      100 Mb/s 
    - [free space optical links](https://en.wikipedia.org/wiki/Long-range_optical_wireless_communication)

- optical cables need amplification around 1000km
- [attenuation](https://en.wikipedia.org/wiki/Attenuation): light being absorbed
- [dispersion](https://en.wikipedia.org/wiki/Dispersion_(optics)): speed of light (velocity) depends on wavelength

## Wavelength division Multiplexing - WDM

### Course WDM

- for more local communications
    - home
    - city
- cheap technology with limited capacity and distance
- typically 16 channels per fibre

### Long distance transmission

- because of attenuation optical needs to be amplified when travelling long distances
- OTN - optical transmission network

## basic optical networking

Traffic is routed in a sort of circle and wavelength multiplexing can be used to add/drop nodes.
By using filters for the wavelength you can add/drop nodes (called optical add/drop multiplexing - **OADM**)
Reconfigurable OADM is called **ROADM**, this is not done packet by packet and is not very dynamic.

- optical forwarding is much more power efficient than routing
    - id traffic is only bypassing (forwarded), routers only cause delay 

## controlling

- controlling of a optical network is done through a **Network Management system (NMS)**
    - need to work across vendors and network layers
- **software defined networks (SDN)**
    - Rising field

## Fibre optics as sensor

- fibre optic cables can be used as sensors through different techniques:
    - DAS - distributed accoustic sensing
        - high sensitivity
        - can track position info
        - expensive and does not scale
    - SoP - state of polarization
        - can not track position info, but position can be inferred with other data
        - detect if cable is touched or moved
        - cheaper and scales better than DAS



