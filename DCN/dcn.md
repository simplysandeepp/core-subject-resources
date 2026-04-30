Data Communication and Networking

# Data Communications & Computer Networks — MCQ Quiz

An interactive MCQ quiz web app covering core topics from Data Communications and Computer Networks, designed for B.Tech placement exam preparation.

---

## Topics Covered

- 1.1 Process of Data Communication & its Components
- 1.2 Protocols, Standards, Bandwidth, Baud Rate & Bit Rate
- 1.3 Modes of Communication (Simplex, Half Duplex, Full Duplex)
- 1.4 Analog & Digital Signals and Conversions (ADC/DAC)
- 1.5 Fundamentals of Computer Networks
- 1.6 Classification of Networks (LAN, MAN, WAN)

---

## Features

- 25 placement-oriented MCQs with detailed explanations
- Filter questions by topic
- Live score tracking
- Instant feedback with correct answer highlighting
- Reshuffle and restart anytime

---

## How to Use

1. Open the quiz in your browser
2. Select a topic filter or attempt all questions
3. Click an option to answer
4. Read the explanation after each question
5. Hit **Restart** to reshuffle and retry

---

## Tech Stack

- HTML / CSS / Vanilla JavaScript
- No external dependencies

---

## All 25 MCQs with Answers & Explanations

---

### 1.1 Data Communication (5 Questions)

---

**Q1. Which of the following is NOT a component of a data communication system?**

- A) Transmitter
- B) Protocol
- C) **Router** ✅
- D) Message

> **Explanation:** The 5 core components are: Transmitter, Receiver, Medium, Message, and Protocol. A Router is a networking device, not a basic component of the communication model.

---

**Q2. In data communication, the 'medium' refers to:**

- A) The message being sent
- B) **The physical path through which data travels** ✅
- C) The device that encodes the signal
- D) The set of rules governing transmission

> **Explanation:** The medium (also called the transmission medium or channel) is the physical path over which data is transmitted — e.g., twisted pair, coaxial cable, fiber optics, or wireless.

---

**Q3. Which component of data communication is responsible for converting the message into a transmittable signal?**

- A) Receiver
- B) Medium
- C) **Transmitter** ✅
- D) Protocol

> **Explanation:** The Transmitter encodes/converts the message into a form suitable for transmission over the chosen medium.

---

**Q4. Data communication is considered effective if it delivers the message:**

- A) As large as possible
- B) **Accurately, timely, and to the correct destination** ✅
- C) With maximum compression
- D) Without any encoding

> **Explanation:** The three criteria for effective data communication are: Delivery (to correct destination), Accuracy (error-free), Timeliness (in time — especially for real-time data like video).

---

**Q5. Which layer of the OSI model is responsible for defining protocols?**

- A) Physical Layer
- B) Data Link Layer
- C) **All layers define their own protocols** ✅
- D) Only Application Layer

> **Explanation:** Each layer of the OSI model has its own protocols. Physical layer protocols define electrical signals; Data link defines framing; Network defines routing, etc. Protocols exist at every layer.

---

### 1.2 Protocols, Standards, Bandwidth, Baud Rate & Bit Rate (5 Questions)

---

**Q6. Baud rate is defined as:**

- A) Number of bits transmitted per second
- B) **Number of signal changes per second** ✅
- C) Number of bytes transmitted per second
- D) Bandwidth in Hz

> **Explanation:** Baud rate = number of signal unit changes (symbols) per second. It equals bit rate only when each symbol carries 1 bit. If each symbol carries n bits, bit rate = Baud rate × n.

---

**Q7. If baud rate is 1000 and each signal element carries 4 bits, the bit rate is:**

- A) 250 bps
- B) 1000 bps
- C) **4000 bps** ✅
- D) 2000 bps

> **Explanation:** Bit rate = Baud rate × bits per symbol = 1000 × 4 = 4000 bps. This is the key relationship tested in placement exams.

---

**Q8. Which of the following is a de facto standard?**

- A) IEEE 802.3
- B) **TCP/IP** ✅
- C) ISO 9660
- D) RS-232

> **Explanation:** TCP/IP is a de facto standard — it became widely adopted through usage rather than being formally approved by a standards body first. IEEE 802.3 is a de jure (official) standard by IEEE.

---

**Q9. The organization responsible for Internet standards (RFCs) is:**

- A) IEEE
- B) ISO
- C) **IETF** ✅
- D) ITU

> **Explanation:** IETF (Internet Engineering Task Force) publishes RFCs (Request for Comments) which define Internet protocols. IEEE handles networking hardware standards; ISO handles broader international standards; ITU handles telecom.

---

**Q10. Nyquist's theorem for a noiseless channel states that maximum data rate =**

- A) **2 × Bandwidth × log₂(L)** ✅
- B) Bandwidth × log₂(L)
- C) 2 × Bandwidth / log₂(L)
- D) Bandwidth / 2

> **Explanation:** Nyquist: Max bit rate = 2B × log₂(L), where B = bandwidth in Hz and L = number of discrete signal levels. Shannon's theorem adds noise consideration: C = B × log₂(1 + S/N).

---

### 1.3 Modes of Communication (4 Questions)

---

**Q11. In which communication mode can data flow in both directions, but only one direction at a time?**

- A) Simplex
- B) **Half Duplex** ✅
- C) Full Duplex
- D) Multiplex

> **Explanation:** Half duplex allows bidirectional communication but only one direction at a time (e.g., walkie-talkie). Simplex = one direction only. Full duplex = both directions simultaneously.

---

**Q12. A traditional TV broadcast is an example of:**

- A) Full Duplex
- B) Half Duplex
- C) **Simplex** ✅
- D) Time-Division Duplex

> **Explanation:** TV broadcasting is simplex — data (video/audio) flows only from broadcaster to viewer with no return channel. Keyboard-to-CPU is another classic simplex example.

---

**Q13. Which of the following is a Full Duplex communication system?**

- A) Walkie-talkie
- B) Keyboard
- C) **Telephone** ✅
- D) Television

> **Explanation:** A telephone allows both parties to speak and listen simultaneously — that's full duplex. Walkie-talkie = half duplex; Keyboard = simplex; Television = simplex.

---

**Q14. Which of these uses Half-Duplex communication?**

- A) Mobile phone call
- B) Cable TV
- C) **Walkie-talkie** ✅
- D) Computer keyboard

> **Explanation:** Walkie-talkie is the classic half-duplex example: one person talks while the other listens; they take turns. Mobile calls = full duplex; Cable TV = simplex; Keyboard = simplex.

---

### 1.4 Analog & Digital Signals and Conversions (5 Questions)

---

**Q15. Which conversion technique is used in a modem to send computer data over phone lines?**

- A) ADC (Analog to Digital)
- B) **DAC (Digital to Analog)** ✅
- C) PCM
- D) Delta Modulation

> **Explanation:** A modem (modulator-demodulator) uses DAC (Digital-to-Analog Conversion) when sending data from computer over phone lines, and ADC when receiving. 'Modem' literally means modulate + demodulate.

---

**Q16. PCM (Pulse Code Modulation) is used for:**

- A) Digital to Analog conversion
- B) **Analog to Digital conversion** ✅
- C) Amplifying analog signals
- D) Compressing digital data

> **Explanation:** PCM is an ADC technique: it samples an analog signal at regular intervals, quantizes the samples, and encodes them as binary. It's used in audio CDs, digital telephony, etc.

---

**Q17. In ASK (Amplitude Shift Keying), the digital data is represented by:**

- A) Varying the frequency of the carrier
- B) **Varying the amplitude of the carrier** ✅
- C) Varying the phase of the carrier
- D) Varying the bit rate

> **Explanation:** ASK = Digital-to-Analog conversion where binary 1 and 0 are represented by two different amplitudes of the carrier signal. FSK uses frequency; PSK uses phase.

---

**Q18. Sampling rate in ADC must be at least ___ the highest frequency in the signal (Nyquist Sampling Theorem):**

- A) Equal to
- B) Half of
- C) **Twice** ✅
- D) Four times

> **Explanation:** Nyquist Sampling Theorem: sampling rate ≥ 2 × fmax. If a signal has max frequency 4 kHz, it must be sampled at ≥ 8000 samples/sec to reconstruct perfectly.

---

**Q19. Quantization noise/error in ADC occurs due to:**

- A) High sampling frequency
- B) **Rounding of sample values to nearest quantization level** ✅
- C) Using too many bits per sample
- D) Signal amplification

> **Explanation:** Quantization error arises because continuous amplitude values are rounded to the nearest discrete quantization level. More bits per sample = more levels = less quantization error.

---

### 1.5 Fundamentals of Computer Networks (3 Questions)

---

**Q20. Which of the following is NOT a primary benefit of a computer network?**

- A) Resource sharing
- B) Increased data redundancy for backup
- C) **Faster CPU processing speed** ✅
- D) Communication and collaboration

> **Explanation:** CPU processing speed is a hardware characteristic unaffected by networking. Networks provide resource sharing (printers, storage), communication, reliability via redundancy, and cost savings.

---

**Q21. The concept of 'resource sharing' in a network primarily means:**

- A) All computers have the same hardware
- B) **Hardware and software resources are accessible to authorized users** ✅
- C) Each node has its own dedicated resources
- D) Network resources are shared only with external users

> **Explanation:** Resource sharing = making hardware (printers, storage) and software (applications, databases) available to authorized network users, reducing duplication and cost.

---

**Q22. A distributed processing network is one where:**

- A) All processing is done at a central server
- B) **Tasks are divided among multiple computers** ✅
- C) Each computer works in isolation
- D) Only one computer processes at a time

> **Explanation:** Distributed processing divides a task into smaller subtasks handled by multiple computers. This improves performance, fault tolerance, and scalability — key motivation for building networks.

---

### 1.6 Classification of Networks (4 Questions)

---

**Q23. Which network type typically spans a city or metropolitan area?**

- A) LAN
- B) WAN
- C) **MAN** ✅
- D) PAN

> **Explanation:** MAN (Metropolitan Area Network) spans a city or large campus — typically 5–50 km. LAN = single building/floor; WAN = country/continent; PAN = personal space (~10m).

---

**Q24. IEEE 802.11 is a standard for:**

- A) Ethernet (LAN)
- B) **Wi-Fi (WLAN)** ✅
- C) WAN routing
- D) Bluetooth

> **Explanation:** IEEE 802.11 defines the Wi-Fi standards (WLAN). IEEE 802.3 = Ethernet (wired LAN); 802.15 = Bluetooth/WPAN; WAN uses carrier-specific protocols like MPLS, Frame Relay.

---

**Q25. The Internet is the best example of:**

- A) LAN
- B) MAN
- C) **WAN** ✅
- D) CAN

> **Explanation:** The Internet is the largest WAN — it spans the entire globe using a combination of leased lines, satellite links, fiber optic cables, and routers. It is owned and operated by multiple ISPs.

---

## Quick Reference Cheat Sheet

| Concept | Formula / Key Fact |
|---|---|
| Bit Rate | Baud Rate × bits per symbol |
| Nyquist (noiseless) | 2B × log₂(L) |
| Shannon (noisy) | B × log₂(1 + S/N) |
| Simplex | One direction only (TV, keyboard) |
| Half Duplex | Both directions, one at a time (walkie-talkie) |
| Full Duplex | Both directions simultaneously (telephone) |
| ADC | Analog → Digital (PCM, sampling) |
| DAC | Digital → Analog (modem sending data) |
| LAN | Building/campus, high speed, low error |
| MAN | City-wide, ~5–50 km |
| WAN | Country/global (Internet) |
| IETF | Publishes RFCs, Internet standards |
| TCP/IP | De facto standard |
| IEEE 802.3 | Ethernet |
| IEEE 802.11 | Wi-Fi |

---

# Unit II — Transmission Media & Switching | MCQ Quiz

Interactive MCQ quiz for B.Tech placement preparation covering Transmission Media, Multiplexing, and Switching.

---

## Topics Covered

- 2.1 Guided Transmission Media (Twisted-Pair, Coaxial, Fiber-Optic)
- 2.2 Unguided Transmission Media (Radio, Microwave, Infrared, Satellite)
- 2.3 Line-of-Sight, Point-to-Point, Broadcast Transmission
- 2.4 Multiplexing (FDM, TDM)
- 2.5 Switching (Circuit-Switched, Packet-Switched)

---

## Features

- 25 placement-oriented MCQs
- Answers hidden — listed separately at the bottom
- Detailed explanations for every question
- Quick reference cheat sheet included

---

## All 25 MCQs

---

### 2.1 Guided Transmission Media

---

**Q1. Which guided medium offers the highest bandwidth and is completely immune to electromagnetic interference?**

- A) Twisted-Pair Cable
- B) Coaxial Cable
- C) Fiber-Optic Cable
- D) Shielded Twisted Pair

---

**Q2. The main advantage of Shielded Twisted Pair (STP) over Unshielded Twisted Pair (UTP) is:**

- A) Higher data rate
- B) Lower cost
- C) Better noise immunity due to shielding
- D) Easier installation

---

**Q3. Which of the following cables is commonly used in cable television (CATV) networks?**

- A) Twisted-Pair
- B) Coaxial Cable
- C) Fiber-Optic Cable
- D) Infrared

---

**Q4. In fiber-optic communication, data is transmitted in the form of:**

- A) Electrical signals
- B) Radio waves
- C) Light pulses
- D) Microwave signals

---

**Q5. Which type of fiber-optic cable uses a single path for light transmission and is used for long-distance communication?**

- A) Multimode Step-Index
- B) Multimode Graded-Index
- C) Single-Mode
- D) Dual-Mode

---

### 2.2 Unguided Transmission Media

---

**Q6. Which unguided medium uses frequencies between 3 kHz and 1 GHz and can penetrate walls?**

- A) Infrared
- B) Microwaves
- C) Radio Waves
- D) Satellite

---

**Q7. Infrared transmission is used in:**

- A) Long-distance communication
- B) TV remotes and short-range device communication
- C) Satellite broadcasting
- D) Mobile telephony

---

**Q8. Geostationary satellites orbit the Earth at an altitude of approximately:**

- A) 200 km
- B) 2000 km
- C) 36,000 km
- D) 100,000 km

---

**Q9. Which of the following is a disadvantage of satellite communication?**

- A) Wide coverage area
- B) High propagation delay (~270 ms)
- C) Supports broadcast communication
- D) Works in remote areas

---

**Q10. Microwave transmission requires:**

- A) Physical cables
- B) Line-of-sight between antennas
- C) Underwater cables
- D) No antenna alignment

---

### 2.3 Line-of-Sight, Point-to-Point, Broadcast

---

**Q11. Line-of-Sight (LOS) transmission means:**

- A) Data travels through the ground
- B) Transmitter and receiver must have a clear, unobstructed path
- C) Signals can pass through any obstacle
- D) Communication uses reflected signals only

---

**Q12. Which of the following is an example of Point-to-Point transmission?**

- A) FM Radio broadcasting
- B) Television broadcasting
- C) A leased telephone line between two offices
- D) Satellite TV

---

**Q13. Broadcast transmission differs from point-to-point in that:**

- A) Only one receiver exists
- B) Data is sent from one sender to all receivers simultaneously
- C) It requires fiber optic cables
- D) It is always encrypted

---

**Q14. Which transmission type does AM/FM radio use?**

- A) Point-to-Point
- B) Simplex Point-to-Point
- C) Broadcast
- D) Half-Duplex Point-to-Point

---

### 2.4 Multiplexing

---

**Q15. Multiplexing is used to:**

- A) Encrypt data before transmission
- B) Send multiple signals over a single communication channel simultaneously
- C) Convert analog to digital signals
- D) Increase the noise in a channel

---

**Q16. In Frequency Division Multiplexing (FDM):**

- A) Each channel gets the full bandwidth for a fixed time slot
- B) Each channel is assigned a unique frequency band within the total bandwidth
- C) Signals are time-interleaved
- D) Only digital signals can be multiplexed

---

**Q17. Time Division Multiplexing (TDM) is best suited for:**

- A) Analog signals only
- B) Digital signals
- C) Optical signals only
- D) Radio frequency signals

---

**Q18. In synchronous TDM, if there are 4 channels each sending at 1 Mbps, the total line speed must be at least:**

- A) 1 Mbps
- B) 2 Mbps
- C) 4 Mbps
- D) 8 Mbps

---

**Q19. Which multiplexing technique is used in cable TV to carry multiple channels?**

- A) TDM
- B) FDM
- C) WDM
- D) CDM

---

**Q20. Wavelength Division Multiplexing (WDM) is essentially FDM applied to:**

- A) Radio waves
- B) Fiber-optic cables
- C) Coaxial cables
- D) Twisted pair cables

---

### 2.5 Switching

---

**Q21. In a circuit-switched network, a dedicated path is established:**

- A) Only during data transfer
- B) Before communication begins and maintained for the entire duration
- C) Dynamically for each packet
- D) Only for multimedia traffic

---

**Q22. The main disadvantage of circuit switching compared to packet switching is:**

- A) Higher data rates
- B) Wasted bandwidth when no data is being sent
- C) More complex routing
- D) Higher error rates

---

**Q23. In packet switching, each packet:**

- A) Follows the same fixed path as all other packets
- B) May take a different path to reach the destination
- C) Requires a dedicated channel
- D) Cannot be reassembled at the destination

---

**Q24. Which switching technique is used by the modern Internet?**

- A) Circuit Switching
- B) Message Switching
- C) Packet Switching
- D) Cell Switching only

---

**Q25. Store-and-forward is a characteristic of:**

- A) Circuit Switching
- B) Dedicated line switching
- C) Packet Switching
- D) Frequency switching

---

## Quick Reference Cheat Sheet

| Concept | Key Fact |
|---|---|
| Twisted Pair | Cheapest, prone to EMI, used in telephone/LAN |
| Coaxial Cable | Better shielding, used in CATV, longer range than TP |
| Fiber Optic | Highest bandwidth, immune to EMI, uses light pulses |
| Single-Mode Fiber | One light path, long distance, expensive |
| Multimode Fiber | Multiple paths, short distance, cheaper |
| Radio Waves | 3 kHz–1 GHz, penetrates walls, omnidirectional |
| Microwave | 1–300 GHz, LOS required, point-to-point |
| Infrared | Short range, no wall penetration (TV remotes) |
| Geostationary Satellite | 36,000 km altitude, ~270 ms delay |
| FDM | Divides bandwidth into frequency bands (analog) |
| TDM | Divides time into slots (digital) |
| WDM | FDM for fiber optics (different wavelengths) |
| Circuit Switching | Dedicated path, used in PSTN/telephone |
| Packet Switching | No dedicated path, used in Internet |
| Store-and-Forward | Packet received fully before forwarding (packet switching) |

---

## Explanation Key

**Q1 — C:** Fiber-optic uses light and is immune to EMI with virtually unlimited bandwidth compared to copper media.

**Q2 — C:** STP has a metallic shield around the twisted pairs that reduces electromagnetic interference, making it better for noisy environments.

**Q3 — B:** Coaxial cable's shielding and bandwidth make it ideal for CATV (Cable TV). It carries multiple channels via FDM.

**Q4 — C:** Fiber-optic cables transmit data as pulses of light (photons), not electrical signals — this is why they are immune to EMI.

**Q5 — C:** Single-mode fiber has a very narrow core (~8–10 µm), allowing only one light path, making it ideal for long-distance, high-bandwidth links.

**Q6 — C:** Radio waves (3 kHz–1 GHz) are omnidirectional and can pass through walls, making them ideal for AM/FM radio and Wi-Fi.

**Q7 — B:** Infrared is blocked by walls and works only over short distances — used in TV remotes, IrDA ports, and short-range device control.

**Q8 — C:** Geostationary (GEO) satellites orbit at ~35,786 km above the equator and appear stationary relative to Earth.

**Q9 — B:** The ~36,000 km altitude means a round-trip signal takes ~270 ms — significant latency for real-time applications like VoIP or gaming.

**Q10 — B:** Microwave is a LOS technology — antennas must be aligned with no obstructions between them, which is why towers are placed on hills/rooftops.

**Q11 — B:** LOS means the transmitter and receiver must have a clear, direct, unobstructed path — walls, terrain, and buildings are blockers.

**Q12 — C:** A leased line between two specific offices is a classic point-to-point link — dedicated to exactly two endpoints.

**Q13 — B:** In broadcast, one sender transmits and all nodes in the network receive the signal — e.g., radio, TV, Wi-Fi beacons.

**Q14 — C:** AM/FM radio is one-to-many — one station transmits, all radios in range receive. This is the definition of broadcast.

**Q15 — B:** Multiplexing combines multiple signals onto a single channel, maximizing the use of expensive transmission infrastructure.

**Q16 — B:** In FDM, the total bandwidth is divided into non-overlapping frequency bands — each user/channel gets its own band permanently.

**Q17 — B:** TDM works by interleaving time slots and is inherently designed for digital signals — it's used in T1/E1 digital telephone lines.

**Q18 — C:** Synchronous TDM allocates one slot per channel regardless of activity. 4 channels × 1 Mbps = 4 Mbps minimum line speed.

**Q19 — B:** Cable TV uses FDM — each TV channel is assigned a different frequency band on the same coaxial cable.

**Q20 — B:** WDM applies the FDM concept to fiber optics using different wavelengths (colors) of light — enabling terabits/sec on a single fiber.

**Q21 — B:** Circuit switching sets up a dedicated end-to-end path before data transfer begins (like a phone call) and keeps it for the session.

**Q22 — B:** In circuit switching, the allocated bandwidth sits idle when no data is being transmitted — wasteful for bursty data like web traffic.

**Q23 — B:** Packet switching is connectionless — each packet has a header with destination info and routers decide the best path independently per packet.

**Q24 — C:** The Internet uses packet switching — data is broken into packets that are routed independently through the network.

**Q25 — C:** Store-and-forward means each router receives the entire packet, checks it, then forwards it — a core characteristic of packet switching.

---

## Answer Key

| Q | Ans | Q | Ans | Q | Ans | Q | Ans | Q | Ans |
|---|---|---|---|---|---|---|---|---|---|
| 1 | C | 6 | C | 11 | B | 16 | B | 21 | B |
| 2 | C | 7 | B | 12 | C | 17 | B | 22 | B |
| 3 | B | 8 | C | 13 | B | 18 | C | 23 | B |
| 4 | C | 9 | B | 14 | C | 19 | B | 24 | C |
| 5 | C | 10 | B | 15 | B | 20 | B | 25 | C |

---

## Target Audience

B.Tech students preparing for placement exams — TCS, Infosys, Wipro, Accenture, GATE, and university exams.

---

## License

MIT
