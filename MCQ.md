# Multiple Choice Questions - Communications Engineering

## Unit 1: Basics of Communication Systems

### Introduction and Future of Communications

1. **Which generation of mobile network is capable of delivering speeds of 1 terabyte/second?**
   - a) 4G
   - b) 5G
   - c) 6G
   - d) 7G
   
   **Answer: c) 6G** - 6G network is capable of delivering speed of 1 terabyte/second with air latency less than 100 microseconds.

2. **What is the latency of 5G networks?**
   - a) 50 ms
   - b) 5 ms
   - c) 500 ms
   - d) 0.5 ms
   
   **Answer: b) 5 ms** - 5G networks have 5ms latency compared to 50ms for 4G/LTE networks.

3. **Which protocol governs the transmission of data across networks?**
   - a) HTTP
   - b) FTP
   - c) TCP/IP
   - d) SMTP
   
   **Answer: c) TCP/IP** - Computer engineers design protocols such as TCP/IP for seamless data exchange.

4. **What does IoT stand for?**
   - a) Internet of Technology
   - b) Internet of Things
   - c) Integration of Technology
   - d) Interface of Terminals
   
   **Answer: b) Internet of Things** - IoT includes smart homes, wearable devices, and connected vehicles.

### Frequency Spectrum and Bandwidth

5. **What is the frequency range of FM Radio broadcasting?**
   - a) 30-88 MHz
   - b) 88-108 MHz
   - c) 108-150 MHz
   - d) 150-300 MHz
   
   **Answer: b) 88-108 MHz** - FM Radio operates in the VHF band at 88-108 MHz.

6. **Which frequency band is used for AM Radio?**
   - a) VLF (3-30 kHz)
   - b) LF (30-300 kHz)
   - c) MF (300 kHz - 3 MHz)
   - d) HF (3-30 MHz)
   
   **Answer: c) MF (300 kHz - 3 MHz)** - AM Radio operates at 535-1705 kHz in the MF band.

7. **What is the bandwidth of voice grade circuits?**
   - a) 2 kHz
   - b) 4 kHz
   - c) 8 kHz
   - d) 16 kHz
   
   **Answer: b) 4 kHz** - Voice grade circuits have a bandwidth of 4 kHz (0-4000 Hz).

8. **VHF (Very High Frequency) operates in which range?**
   - a) 3-30 MHz
   - b) 30-300 MHz
   - c) 300 MHz - 3 GHz
   - d) 3-30 GHz
   
   **Answer: b) 30-300 MHz** - VHF includes TV channels 2-6 and FM radio.

9. **GPS operates at approximately which frequency?**
   - a) 500 MHz
   - b) 1.575 GHz
   - c) 2.4 GHz
   - d) 5 GHz
   
   **Answer: b) 1.575 GHz** - GPS L1 frequency is at 1.575 GHz in the L-band.

10. **Which frequency band includes satellite communications using the Ku-band?**
    - a) 3-8 GHz
    - b) 12-18 GHz
    - c) 27-40 GHz
    - d) 40-75 GHz
    
    **Answer: b) 12-18 GHz** - Ku-band operates in the 12-18 GHz range.

### Analog and Digital Systems

11. **According to the Nyquist Theorem, what is the maximum bit rate for a voice channel with 8 levels per signal element?**
    - a) 9000 bps
    - b) 12000 bps
    - c) 18000 bps
    - d) 24000 bps
    
    **Answer: c) 18000 bps** - Max bit rate = 2 × 3000 × log₂(8) = 18000 bps.

12. **What is the theoretical maximum bit rate according to Shannon-Hartley Law for a telephone line with S/N ratio of 1000?**
    - a) 10000 bps
    - b) 20000 bps
    - c) 30000 bps
    - d) 40000 bps
    
    **Answer: c) 30000 bps** - Max bit rate = 3000 × log₂(1000) ≈ 30000 bps.

13. **Who invented the baud unit of measurement?**
    - a) Shannon
    - b) Nyquist
    - c) Baudot
    - d) Hartley
    
    **Answer: c) Baudot** - The baud is named after Émile Baudot (1845-1903).

14. **What type of information source produces values defined on a continuum?**
    - a) Digital
    - b) Analog
    - c) Binary
    - d) Discrete
    
    **Answer: b) Analog** - Analog sources like human voice produce continuous values.

15. **What is the common deterioration measure for digital systems?**
    - a) Signal to Noise Ratio (SNR)
    - b) Bit Error Rate (BER)
    - c) Bandwidth Efficiency
    - d) Power Consumption
    
    **Answer: b) Bit Error Rate (BER)** - Digital systems use BER while analog systems use SNR.

### Multiplexing

16. **What is the sampling rate required for a 4 kHz bandwidth signal according to Nyquist Sampling Theorem?**
    - a) 4000 samples/sec
    - b) 6000 samples/sec
    - c) 8000 samples/sec
    - d) 16000 samples/sec
    
    **Answer: c) 8000 samples/sec** - The signal must be sampled at a rate greater than twice its bandwidth.

17. **How many time slots are in an E-1 frame?**
    - a) 24
    - b) 30
    - c) 32
    - d) 64
    
    **Answer: c) 32** - E-1 has 32 8-bit time slots, with 30 used for subscriber PCM.

18. **What is the bit rate of an E-1 signal?**
    - a) 1.544 Mbit/s
    - b) 2.048 Mbit/s
    - c) 8.448 Mbit/s
    - d) 34.368 Mbit/s
    
    **Answer: b) 2.048 Mbit/s** - 8000 frames/s × 256 bits/frame = 2.048 Mbit/s.

19. **In an E-1 frame, which time slot contains common channel signaling?**
    - a) Slot 0
    - b) Slot 1
    - c) Slot 16
    - d) Slot 31
    
    **Answer: c) Slot 16** - Slot 16 contains CCS or channel associated condition bits.

20. **What does PDH stand for?**
    - a) Parallel Digital Hierarchy
    - b) Plesiochronous Digital Hierarchy
    - c) Progressive Digital Hierarchy
    - d) Primary Digital Hierarchy
    
    **Answer: b) Plesiochronous Digital Hierarchy** - The European version of digital multiplexing hierarchy.

### DSL Technology

21. **How many tones does ADSL use for Discrete Multitone signaling (DMT)?**
    - a) 128
    - b) 256
    - c) 512
    - d) 1024
    
    **Answer: b) 256** - ADSL uses 256 tones while VDSL2 uses 4096 tones.

22. **What is the passband width of each DMT tone in ADSL?**
    - a) 2.156 kHz
    - b) 4.3125 kHz
    - c) 8.625 kHz
    - d) 10 kHz
    
    **Answer: b) 4.3125 kHz** - Each tone has a 4.3125 kHz passband.

23. **What is the maximum downstream rate for ADSL2+?**
    - a) 6 Mbps
    - b) 8 Mbps
    - c) 16 Mbps
    - d) 52 Mbps
    
    **Answer: c) 16 Mbps** - ADSL2+ provides up to 16 Mbps downstream.

24. **What does POTS stand for in DSL terminology?**
    - a) Public Open Telephone System
    - b) Plain Old Telephone System
    - c) Private Online Telephone Service
    - d) Primary Optical Telephone System
    
    **Answer: b) Plain Old Telephone System** - POTS refers to the traditional voice telephone service.

25. **VDSL2 can provide aggregate data rates up to:**
    - a) 100 Mbit/s
    - b) 200 Mbit/s
    - c) 300+ Mbit/s
    - d) 500 Mbit/s
    
    **Answer: c) 300+ Mbit/s** - VDSL2 with Vplus/35b can provide up to 300+ Mbit/s.

### Synchronous and Asynchronous Transmission

26. **In asynchronous transmission, what is used to synchronize each character?**
    - a) Clock signal
    - b) Start and stop bits
    - c) Preamble
    - d) CRC
    
    **Answer: b) Start and stop bits** - Each character is individually timed with start and stop bits.

27. **Which is an example of high-speed asynchronous transmission?**
    - a) RS-232
    - b) ATM
    - c) HDLC
    - d) SDLC
    
    **Answer: b) ATM** - Asynchronous Transfer Mode is a high-speed asynchronous technology.

28. **What type of transmission requires more hardware and software resources?**
    - a) Asynchronous
    - b) Synchronous
    - c) Simplex
    - d) Half-duplex
    
    **Answer: b) Synchronous** - Synchronous transmission requires more resources but enables high-speed communication.

## Unit 1-2: Transmission Media

### Guided Transmission Media

29. **What is the repeater spacing for optical fiber?**
    - a) 2 km
    - b) 9 km
    - c) 20 km
    - d) 40 km
    
    **Answer: d) 40 km** - Optical fiber has 40 km repeater spacing compared to 2 km for twisted pair.

30. **What is the typical attenuation of optical fiber?**
    - a) 0.2-0.5 dB/km
    - b) 0.7 dB/km
    - c) 7 dB/km
    - d) 20 dB/km
    
    **Answer: a) 0.2-0.5 dB/km** - Optical fiber has very low attenuation.

31. **Which guided medium has a frequency range of 0 to 500 MHz?**
    - a) Twisted pair
    - b) Coaxial cable
    - c) Optical fiber
    - d) UTP
    
    **Answer: b) Coaxial cable** - Coaxial cable operates from 0 to 500 MHz.

32. **What type of twisted pair is the cheapest and easiest to install?**
    - a) STP
    - b) UTP
    - c) FTP
    - d) SFTP
    
    **Answer: b) UTP** - Unshielded Twisted Pair is the cheapest and easiest to install.

33. **Optical fiber carries data using:**
    - a) Radio waves
    - b) Microwaves
    - c) Light
    - d) Electric current
    
    **Answer: c) Light** - Light travels along the fiber by total internal reflection.

### Wireless Transmission

34. **At what height do geostationary satellites orbit?**
    - a) 400 km
    - b) 2,000 km
    - c) 20,000 km
    - d) 35,863 km
    
    **Answer: d) 35,863 km** - Geostationary satellites remain above the equator at 35,863 km.

35. **What is the typical distance between terrestrial microwave repeater stations?**
    - a) 10 km
    - b) 25 km
    - c) 50 km
    - d) 100 km
    
    **Answer: c) 50 km** - Due to Earth's curvature, repeaters are needed about 50 km apart.

36. **Which antenna type radiates signals in all directions?**
    - a) Parabolic
    - b) Directional
    - c) Omnidirectional
    - d) Yagi
    
    **Answer: c) Omnidirectional** - Omnidirectional antennas radiate in all directions.

37. **Microwaves occupy which frequency range?**
    - a) 30 MHz - 300 MHz
    - b) 300 MHz - 3 GHz
    - c) 300 MHz - 300 GHz
    - d) 3 GHz - 300 GHz
    
    **Answer: c) 300 MHz - 300 GHz** - Microwaves span from 300 MHz to 300 GHz (or 1mm to 1m wavelength).

38. **Which satellite band has the major problem of rain interference?**
    - a) C Band
    - b) K Band
    - c) L Band
    - d) S Band
    
    **Answer: b) K Band** - K bands are smaller and cheaper but suffer from rain interference.

### Wireless Networks

39. **What is the IEEE standard for WiFi?**
    - a) IEEE 802.3
    - b) IEEE 802.11
    - c) IEEE 802.15.1
    - d) IEEE 802.15.4
    
    **Answer: b) IEEE 802.11** - WiFi is based on the IEEE 802.11 standard.

40. **What is the IEEE standard for Bluetooth?**
    - a) IEEE 802.3
    - b) IEEE 802.11
    - c) IEEE 802.15.1
    - d) IEEE 802.15.4
    
    **Answer: c) IEEE 802.15.1** - Bluetooth is based on IEEE 802.15.1.

41. **What is the IEEE standard for ZigBee?**
    - a) IEEE 802.3
    - b) IEEE 802.11
    - c) IEEE 802.15.1
    - d) IEEE 802.15.4
    
    **Answer: d) IEEE 802.15.4** - ZigBee is based on IEEE 802.15.4.

42. **How many devices can Bluetooth (v1) connect simultaneously?**
    - a) 4
    - b) 7
    - c) 8
    - d) 16
    
    **Answer: c) 8** - Bluetooth can connect up to 8 devices at a time.

43. **What frequency band do both WiFi and Bluetooth share?**
    - a) 900 MHz
    - b) 2.4 GHz
    - c) 5 GHz
    - d) 60 GHz
    
    **Answer: b) 2.4 GHz** - Both operate in the 2.4 GHz ISM band.

44. **What is the typical range of Bluetooth?**
    - a) 1 meter
    - b) 10 meters
    - c) 100 meters
    - d) 1000 meters
    
    **Answer: b) 10 meters** - Bluetooth Class 2 has a typical range of 10 meters.

### Cellular Networks

45. **What year was 4G developed?**
    - a) 2001
    - b) 2005
    - c) 2010
    - d) 2015
    
    **Answer: c) 2010** - 4G was developed in 2010.

46. **What is the peak downlink data rate for 5G?**
    - a) 1 Gbps
    - b) 10 Gbps
    - c) 20 Gbps
    - d) 100 Gbps
    
    **Answer: c) 20 Gbps** - 5G peak data rate (downlink) is 20 Gbps.

47. **What is the connection density specification for 5G?**
    - a) 10,000 devices/sq.km
    - b) 100,000 devices/sq.km
    - c) 1,000,000 devices/sq.km
    - d) 10,000,000 devices/sq.km
    
    **Answer: c) 1,000,000 devices/sq.km** - 5G supports 1,000,000 devices per square kilometer.

48. **What happens during "handoff" in cellular networks?**
    - a) Call is dropped
    - b) Mobile terminal moves to a new cell
    - c) Data is encrypted
    - d) Signal is amplified
    
    **Answer: b) Mobile terminal moves to a new cell** - Handoff occurs when terminals move between cells.

### Transmission Impairments

49. **What is the formula for decibel (dB)?**
    - a) dB = 20 log₁₀(P2/P1)
    - b) dB = 10 log₁₀(P2/P1)
    - c) dB = log₁₀(P2/P1)
    - d) dB = 10 ln(P2/P1)
    
    **Answer: b) dB = 10 log₁₀(P2/P1)** - This is the standard decibel formula for power ratio.

50. **If the signal power is 10 mW and noise power is 1 μW, what is the SNR?**
    - a) 100
    - b) 1,000
    - c) 10,000
    - d) 100,000
    
    **Answer: c) 10,000** - SNR = 10 mW / 1 μW = 10,000.

51. **Which type of noise is caused by random movement of electrons in a wire?**
    - a) Crosstalk
    - b) Impulse noise
    - c) Thermal noise
    - d) Induced noise
    
    **Answer: c) Thermal noise** - Thermal noise is caused by random electron movement.

52. **Distortion primarily affects which type of signals?**
    - a) Simple signals
    - b) Composite signals
    - c) Digital signals only
    - d) Analog signals only
    
    **Answer: b) Composite signals** - Distortion occurs in composite signals due to different propagation speeds.

## Unit 1-3: Line Coding

53. **In Unipolar NRZ, what represents a binary 0?**
    - a) +V volts
    - b) -V volts
    - c) 0 volts
    - d) Alternating voltage
    
    **Answer: c) 0 volts** - In unipolar NRZ, 0 is represented by zero voltage and 1 by +V.

54. **Which line code has no DC component?**
    - a) Unipolar NRZ
    - b) Unipolar RZ
    - c) Polar NRZ
    - d) Both Unipolar codes
    
    **Answer: c) Polar NRZ** - Polar codes use both +V and -V, eliminating DC component.

55. **In Bipolar AMI, how is the binary 1 represented?**
    - a) Always +V
    - b) Always -V
    - c) Alternating between +V and -V
    - d) Zero voltage
    
    **Answer: c) Alternating between +V and -V** - AMI alternates polarity for 1s.

56. **Manchester coding is a combination of which two schemes?**
    - a) NRZ-L and NRZ-I
    - b) NRZ-L and RZ
    - c) NRZ-I and RZ
    - d) AMI and RZ
    
    **Answer: b) NRZ-L and RZ** - Manchester combines NRZ-L and RZ with mid-bit transitions.

57. **What is the bandwidth requirement of RZ compared to NRZ?**
    - a) Same bandwidth
    - b) Half the bandwidth
    - c) Twice the bandwidth
    - d) Four times the bandwidth
    
    **Answer: c) Twice the bandwidth** - RZ requires twice the bandwidth due to shorter pulses.

## Unit 2: Traffic Engineering

58. **What is the unit of traffic intensity?**
    - a) Bits per second
    - b) Calls per hour
    - c) Erlang
    - d) Hertz
    
    **Answer: c) Erlang** - Traffic intensity is measured in Erlangs, named after A. K. Erlang.

59. **How is traffic intensity (A) calculated?**
    - a) A = λ / t_m
    - b) A = λ × t_m
    - c) A = λ + t_m
    - d) A = λ - t_m
    
    **Answer: b) A = λ × t_m** - Traffic intensity = arrival rate × average holding time.

60. **In the Erlang B formula, what does N represent?**
    - a) Number of subscribers
    - b) Number of trunks (links)
    - c) Number of calls
    - d) Noise ratio
    
    **Answer: b) Number of trunks (links)** - N is the number of trunks in the Erlang B formula.
