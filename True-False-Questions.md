# True/False Questions - Communications Engineering

## Unit 1: Basics of Communication Systems

### Introduction and Future of Communications

1. **T/F:** Communication has evolved from primitive methods like smoke signals to complex digital networks.
   - **Answer: True** - Communication evolved from smoke signals and carrier pigeons to telegraph, telephone, and complex digital networks.

2. **T/F:** 6G network is capable of delivering speeds of 1 terabyte/second with air latency less than 100 microseconds.
   - **Answer: True** - 6G will deliver 1 terabyte/second or 8,000 gigabits/second with air latency less than 100 microseconds.

3. **T/F:** 5G networks have a latency of about 50 ms, similar to 4G/LTE networks.
   - **Answer: False** - 4G/LTE networks had latency of about 50 ms, while 5G networks have latency of 5ms.

4. **T/F:** IoT (Internet of Things) devices are interconnected through the internet and can transform how we communicate with our surroundings.
   - **Answer: True** - IoT includes smart homes, wearable devices, and connected vehicles.

5. **T/F:** Computer engineers are not involved in designing communication protocols like TCP/IP.
   - **Answer: False** - Computer engineers are responsible for designing protocols such as TCP/IP which govern data transmission across networks.

### Frequency Spectrum and Bandwidth

6. **T/F:** FM Radio broadcasting operates in the frequency range of 88-108 MHz.
   - **Answer: True** - FM Radio operates at 88-108 MHz in the VHF band.

7. **T/F:** VLF (Very Low Frequency) ranges from 30-300 kHz.
   - **Answer: False** - VLF ranges from 3-30 kHz. LF (Low Frequency) ranges from 30-300 kHz.

8. **T/F:** GPS operates in the L-band at around 1.575 GHz.
   - **Answer: True** - GPS L1 frequency is at 1.575 GHz.

9. **T/F:** Bandwidth represents a range of frequencies available for communications.
   - **Answer: True** - Bandwidth is the range of frequencies, e.g., from 300 MHz to 700 MHz is 400 MHz bandwidth.

10. **T/F:** Voice grade circuits have a bandwidth of 8 kHz.
    - **Answer: False** - Voice grade circuits have a bandwidth of 4 kHz (0-4000 Hz).

### Analog and Digital Systems

11. **T/F:** An analog information source produces values defined on a continuum, such as human voice.
    - **Answer: True** - Analog sources produce continuous values while digital sources produce a finite set of symbols.

12. **T/F:** Direct transmission of digital data is possible over a baseband voice signal (telephone channel).
    - **Answer: False** - Direct transmission of digital data is not possible because long sequences of 1's or 0's look like a signal with zero frequency.

13. **T/F:** According to Nyquist Theorem, Max Bit Rate = 2 × carrier bandwidth × log₂(possible values/signal element).
    - **Answer: True** - This is the Nyquist formula for maximum bit rate.

14. **T/F:** Shannon-Hartley Law states that Max bit rate = bandwidth × log₂(1 + S/N).
    - **Answer: True** - This law takes noise into account for calculating maximum bit rate.

15. **T/F:** 33.3 kbps modems reached the theoretical limit defined by Shannon-Hartley Law for telephone lines.
    - **Answer: True** - With S/N ratio of 1000 and 3000 Hz bandwidth, the limit is about 30,000 bps.

### Multiplexing

16. **T/F:** In Frequency Division Multiplexing, voice channels are stacked on high frequency carriers by single sideband amplitude modulation.
    - **Answer: True** - This is the most bandwidth efficient scheme for FDM.

17. **T/F:** According to Nyquist Sampling Theorem, a 4 kHz bandwidth signal must be sampled at least 8000 samples per second.
    - **Answer: True** - The signal must be sampled at a rate greater than twice its bandwidth.

18. **T/F:** In the E-1 frame, there are 24 time slots per frame.
    - **Answer: False** - E-1 has 32 8-bit time slots per frame, with 30 used for subscriber PCM.

19. **T/F:** The E-1 frame has a bit rate of 2.048 Mbit/s.
    - **Answer: True** - 8000 frames/s × 256 bits/frame = 2.048 Mbit/s.

20. **T/F:** PDH stands for Plesiochronous Digital Hierarchy.
    - **Answer: True** - This is the European version of the digital multiplexing hierarchy.

### DSL Technology

21. **T/F:** DSL extends the useful life of POTS copper wires by increasing bandwidth from 3 kHz to 1.1 MHz.
    - **Answer: True** - ADSL extends the frequency range to 1.1 MHz.

22. **T/F:** ADSL uses 256 tones to carry data bits using Discrete Multitone signaling (DMT).
    - **Answer: True** - Each tone has a 4.3125 kHz passband and can carry up to 15 bits.

23. **T/F:** In ADSL, download and upload speeds are the same.
    - **Answer: False** - ADSL is Asynchronous DSL where download and upload speeds differ.

24. **T/F:** VDSL2 can provide aggregate data rates up to 300+ Mbit/s.
    - **Answer: True** - VDSL2 permits transmission of aggregate data rates up to 300+ Mbit/s.

25. **T/F:** Digital communications have greater bandwidth requirements but offer better immunity to noise.
    - **Answer: True** - Digital systems require more bandwidth but provide better noise immunity and security.

### Synchronous and Asynchronous Transmission

26. **T/F:** In asynchronous transmission, the sender and receiver are synchronized with respect to the flow of information.
    - **Answer: False** - In asynchronous transmission, sender and receiver are NOT synchronized with respect to information flow.

27. **T/F:** Asynchronous transmission uses start and stop bits for each character.
    - **Answer: True** - Each character is individually timed using start and stop bits.

28. **T/F:** Synchronous transmission requires more hardware and software resources than asynchronous transmission.
    - **Answer: True** - Synchronous transmission is more resource-intensive but enables high-speed communication.

29. **T/F:** ATM (Asynchronous Transfer Mode) is an example of low-speed asynchronous transmission.
    - **Answer: False** - ATM is an example of high-speed asynchronous transmission.

## Unit 1-2: Transmission Media

### Guided Transmission Media

30. **T/F:** UTP (Unshielded Twisted Pair) is more expensive than STP (Shielded Twisted Pair).
    - **Answer: False** - UTP is the cheapest and easiest to install; STP is more expensive.

31. **T/F:** Optical fiber has a repeater spacing of approximately 40 km.
    - **Answer: True** - Optical fiber has 40 km repeater spacing compared to 2 km for twisted pair.

32. **T/F:** Coaxial cable has a frequency range of 0 to 500 MHz.
    - **Answer: True** - Coaxial cable operates from 0 to 500 MHz.

33. **T/F:** Light travels along a fiber optic cable by bouncing around its edges (total internal reflection).
    - **Answer: True** - This is how fiber optic cables transmit light over long distances.

34. **T/F:** Higher bandwidth gives higher data rate in transmission media.
    - **Answer: True** - Bandwidth is directly related to data rate capacity.

### Wireless Transmission

35. **T/F:** Omnidirectional antennas radiate signals in a particular direction only.
    - **Answer: False** - Omnidirectional antennas radiate signals in all directions; directional/parabolic antennas focus in one direction.

36. **T/F:** Terrestrial microwave requires unobstructed line of sight between source and receiver.
    - **Answer: True** - Microwave transmission needs line of sight with repeaters about 50 km apart.

37. **T/F:** Geostationary satellites remain above the equator at a height of 35,863 km.
    - **Answer: True** - This is the geosynchronous orbit altitude.

38. **T/F:** Higher frequency microwave ranges can easily penetrate walls.
    - **Answer: False** - Higher frequency ranges cannot penetrate walls.

39. **T/F:** The C Band was the first satellite frequency band to be designated.
    - **Answer: True** - C Band (4-8 GHz) was the first to be designated for satellite communications.

### Wireless Networks (WiFi, Bluetooth, ZigBee)

40. **T/F:** WiFi stands for "Wireless Fidelity" and is based on IEEE 802.11 standard.
    - **Answer: True** - WiFi is a trademark of the Wi-Fi Alliance based on IEEE 802.11.

41. **T/F:** Bluetooth operates in the ISM band between 2.4-2.485 GHz with frequency hopping over 79 channels.
    - **Answer: True** - Bluetooth uses frequency hopping at 1600 hops/second.

42. **T/F:** ZigBee has higher power consumption compared to Bluetooth.
    - **Answer: False** - ZigBee is designed for low power consumption, even lower than Bluetooth.

43. **T/F:** Bluetooth can connect up to 65,536 (2^16) devices at a time.
    - **Answer: False** - Bluetooth can connect 8 devices; ZigBee can connect 2^16 devices.

44. **T/F:** WiFi has a typical range of 100 meters while Bluetooth has a range of 10 meters.
    - **Answer: True** - These are the typical ranges for these technologies.

### Cellular Networks

45. **T/F:** 5G peak data rate (downlink) is 20 Gbps.
    - **Answer: True** - 5G offers peak downlink rates of 20 Gbps.

46. **T/F:** 4G was developed in 2001 and provides speeds up to 100 Mbps.
    - **Answer: False** - 4G was developed in 2010, not 2001. 3G was developed in 2001.

47. **T/F:** 6G will operate at frequencies from 95 GHz to 3 terahertz (THz).
    - **Answer: True** - 6G will utilize these extremely high frequencies.

48. **T/F:** In cellular networks, the service area of each base station is called a cell.
    - **Answer: True** - This is the fundamental concept of cellular networks.

### Transmission Impairments

49. **T/F:** Attenuation means loss of energy resulting in a weaker signal.
    - **Answer: True** - Signals lose energy overcoming the resistance of the medium.

50. **T/F:** The decibel formula for attenuation is dB = 10 log₁₀(P2/P1).
    - **Answer: True** - This is the standard formula where P1 is input and P2 is output power.

51. **T/F:** Distortion only affects simple (single frequency) signals, not composite signals.
    - **Answer: False** - Distortion occurs in composite signals due to different propagation speeds of frequency components.

52. **T/F:** Crosstalk is a type of noise caused by interference between two wires.
    - **Answer: True** - Crosstalk occurs when signals from one wire interfere with another.

## Unit 1-3: Line Coding

53. **T/F:** A line code converts digital data (1s and 0s) into a sequence of signals.
    - **Answer: True** - Line coding is used for baseband transmission of digital data.

54. **T/F:** In Unipolar NRZ, the signal level returns to zero between each bit.
    - **Answer: False** - In NRZ (Non-Return to Zero), the signal does NOT return to zero during symbol transmission.

55. **T/F:** Polar line codes have no DC component, making them more energy efficient.
    - **Answer: True** - Polar codes use both positive and negative voltages, eliminating DC component.

56. **T/F:** Manchester coding combines NRZ-L and RZ schemes.
    - **Answer: True** - Manchester coding has a transition in the middle of every symbol.

57. **T/F:** In Bipolar AMI, the 1 symbol alternates between +V and -V while 0 is represented by zero voltage.
    - **Answer: True** - AMI (Alternate Mark Inversion) alternates polarity for 1s.

58. **T/F:** The baud rate formula is S = c × N × 1/r bauds, where N is data rate and r is the ratio between data element and signal element.
    - **Answer: True** - This is the formula relating baud rate to data rate.

## Unit 2: Traffic Engineering

59. **T/F:** One Erlang represents the amount of traffic carried by a trunk that is completely occupied.
    - **Answer: True** - One Erlang equals one call-hour per hour or one call-minute per minute.

60. **T/F:** In a Lost Call (LC) system, blocked calls wait in a queue until a trunk becomes free.
    - **Answer: False** - In Lost Call systems, calls are dropped. In Delay systems, calls wait in a queue.
