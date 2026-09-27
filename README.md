# Flax OS💎
"Turn your computer into supercomputer."

Flax OS is a complete Unix-like operating system based on Linux kernel engineered for users who demand advanced security and privacy without sacrificing usability and stability. It combines multiple proven cybersecurity paradigms into a single, cohesive platform while remaining suitable for everyday, general-purpose computing.

By integrating isolation, anonymity, system hardening, and secure-by-default configurations, Flax OS aims to make strong security accessible to both professionals and privacy-conscious users.

This page is all-in-one manual for our system.

## Ideals:
Our ideals are being:
- General
- Efficient
- Perfect
- Flexible
- Portable
- Safe


## Generality:
### General-purpose ready:
All at once software in a form of a system, suitable for daily tasks such as browsing, development, creativity and productivity, alongside security-focused use cases.

### User-friendly experience:
Advanced security features are exposed in an accessible way, allowing both technical and non-technical users to benefit without complex configuration.

### AI:
Flaxy Fenyx AI - is our AI.


## Efficiency:
### Stability:
Built to ensure reliability and stability, long-term support while giving rapid fixed releases, and access to a mature open-source software ecosystem.

### Hardware support:
We try to support old hardware very well, make old modern new.
FlaxTurbo - is TUI similar to:
- Temple OS
- Commander64
- Turbo C


## Perfection:
Our system is a perfect set up with efficient solutions.


## Flexibilty:
### Multi-Kernel architecture:
Flax system is modular and hierarchical OS.
- Flax OS using FlaxTurbo for minimizing RAM usage.
- This subsystem may be used for specialized networking and isolation function.
- Subsystem running in VM/Container while sharing communication layer.
- Kernel module for communication layer and kernel control.
- Multi-kernel can be used as a microkernel.
- Microkernel can be used for networking stack, which is used as a Whonix-style gateway model.

### Windows compatibility layer:
Flax OS allows to run windows executables using Wine, Proton and dedicated technologies.

### Registry:
Can be edited using Bash scripting language, contains all system settings.

### superpkg / xpkg:
- superpkg is the command-line package manager, and xpkg is a file extension to install superpkg package executables through file manager like on MacOS or Windows.
- Binary package manager.
- Choice or rolling or stable, as for single package or multiple packages.
- Rollback support.


## Portability:
### Live & ephemeral Environments
- Live-session workflows similar to Tails.
- Optional non-persistent modes to avoid long-term data retention, persistent mode can be achived through FlaxBox.
- Reduced forensic footprint through ephemeral system states, full RAM erasement.


## Security:
- Offense
- Defense
We offer both, real security comes from understanding both sides.

### Offense:
Offensive security tools inspired by:
- Kali Linux — Metasploit, NMap, aircrack-ng and other tools.
- Black Arch — dedicated security tools.

### Defense:
### Security-first design:
Flax OS integrates concepts and technologies inspired by:
- Qubes OS — compartmentalization and workload isolation.
- Tails — live OS and non-persistent privacy workflows.
- Whonix — Tor-based network isolation via a dedicated gateway. 
- Kodachi — curated security and anonymity tools.
- Parrot OS — Ingognito mode.

### Privacy-focused by default
Designed to minimize data leakage through hardened defaults, secure networking, and strong encryption.

## Security architecture:
Flax OS follows a defense-in-depth security model, layering multiple protections to reduce attack surfaces and limit the impact of potential compromises.

### System hardening:
- Hardened kernel configuration and secure system defaults.
- Strict permission models and reduced attack surface.

### Isolation & compartmentalization:
FlaxBox - a Knox-like technology, when injected appears as an icon, when pressed demands password, inside you get Fenyx profile, your own file system, apps and so on.

FlaxBox technology allows users to manage security-related components such as containers and virtual machines.

Can be injected with USB or just kept on a computer, the container is fully encyptable, after you eject a box, the RAM block of box itself gets erased.

- Application and service isolation inspired by Qubes OS and Knox principles.
- Use of containers, sandboxes, and Linux namespaces.
- Least-privilege execution to prevent lateral movement.

### Network isolation & anonymity:
- Optional Whonix gateway architecture to isolate network traffic.
- Tor-based routing for anonymized connections.
- Firewall-enforced separation between applications and the network.
- DNS leak prevention and traffic filtering.

### Security & privacy tooling:
- FlaxDefender is a centralized security center similar to Knox of Samsung + Qubes OS manager and YaST, through there you can control firewall rules, Tor routing, metadata cleaning, system monitoring, anti-virus and so on.
- Pre-installed and curated security tools inspired by Kodachi.
- Encryption utilities for data at rest and in transit.
- Monitoring and auditing tools to enhance situational awareness.
- Pentesting tools within system by default, not all but basic ones yes, if you want a full bundle write install the following: "sudo superpkg install flax-pentest".

### Cryptography & data protection:
- Full-disk encryption and encrypted user data by default.
- Modern cryptographic standards for storage and communication.
- Secure credential and key management practices.

### Secure usability:
- Clear security states and configurable privacy modes.
- Balanced automation to prevent misconfiguration.
- Security features designed to be understandable and controllable.

## Philosophy:
Flax system is god's third temple rebuild from ashes.

## Project goals:
- Deliver a secure-by-default hybrid of Linux and Unix binaries.
- Balance security, privacy, and usability by default.
- Make advanced cybersecurity concepts accessible to a wider audience.
- Provide a reliable platform for secure computing and everyday use.

## Target audience:
- Privacy-conscious users.
- Security researchers and students.
- Developers and system administrators.
- Users seeking a hardened Linux desktop for daily use.
- Trinity loyal users.
- Linux and Unix users.

## Project status:
Flax OS is under active development. Features, architecture, and documentation may evolve as the project grows. 

## Contributing:
Contributions, suggestions, bug and vulnerability feedbacks are welcome.
Please open issues for bugs, vulnerabilities and submit pull requests to help improve Flax OS.

## License:
GPL

Flax OS follows the licensing terms of GNU FSF included components.
Refer to individual packages and files for specific license information.
