# SC-VOX

SC-VOX is a dedicated hardware voice communications panel for Star Citizen multi-crew and multi-org operations.

It provides physical, tactile control over up to **7 simultaneous communication channels** using:

- **Simple Radio Standalone (SRS)**
- **In-game VOIP**
- **RSI Spectrum** (planned)

SC-VOX includes real-time LED channel status feedback and per-channel audio management so communications remain clear during high-load operations.

## Platform Integration

SC-VOX is designed to complement the **SC-UCC (Star Citizen Ultra-Cockpit Controller)** button box and shares:

- Distributed processing architecture
- UART communication protocol
- Remote firmware update system

## Design Doctrine

SC-VOX is inspired by real aircraft Audio Control Panels (ACP) and military radio stack workflows.

Guard channel behavior follows aviation doctrine:

- Fixed frequency
- Always monitored
- Cannot be disabled

## Open Source Stack

SC-VOX targets a **100% open source** software stack:

- **OBS Studio** (video)
- **Ardour DAW** (audio)
- **SRS fork** (communications)
- **Custom firmware** (hardware)

No paid software is required.
