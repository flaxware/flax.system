# Flax OS💎
> Turn your computer into a supercomputer.

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/flaxware/flax.system">
    <img src="images/logo.png" alt="Logo" width="150" height="150">
  </a>

  <h3 align="center">FLAX SYSTEM</h3>

  <p align="center">
    <br />
    <a href="https://flaxware.github.io"><strong>Our website»</strong></a>
    <br />
    <br />
    <a href="https://github.com/flaxware/flax.system/blob/main/DOWNLOAD.md">Download</a>
    &middot;
    <a href="https://github.com/flaxware/flax.system/blob/main/LICENSE">View license</a>
    &middot;
    <a href="https://flaxware.github.io/#contact">Contact us</a>
  </p>
</div>

<!-- Description -->
Flax OS is a complete Unix-like operating system based on Linux kernel engineered for users who demand advanced security and privacy without sacrificing usability and stability. It combines multiple proven cybersecurity paradigms into a single, cohesive platform while remaining suitable for everyday, general-purpose computing.

By integrating isolation, anonymity, system hardening, and secure-by-default configurations, Flax OS aims to make strong security accessible to both professionals and privacy-conscious users.

---
## Versions:

 | **Version**            | **Latest build** |
  |---|---|
  | Flax OS 1 "Neo"            | BUILD28   |

---
<!-- MANUAL -->
This page is all-in-one [manual](https://www.mclibre.org/descargar/docs/manuales/the-linux-command-line-v6-202411.pdf) for our system.
## Ideals:
Our ideals are being:
- [General](https://github.com/flaxware/flax.system/#general)
- [Efficient](https://github.com/flaxware/flax.system/#efficient)
- [Perfect](https://github.com/flaxware/flax.system/#perfect)
- [Flexible](https://github.com/flaxware/flax.system/#flexible)
- [Portable](https://github.com/flaxware/flax.system/#portable)
- [Safe](https://github.com/flaxware/flax.system/#safe)
> [Philosophy](https://github.com/flaxware/flax.system/#philosophy)
---
## General:
All at once software in a form of a system, suitable for daily tasks such as browsing, development, creativity and productivity, alongside security-focused use cases; Advanced security features are exposed in an accessible way, allowing both technical and non-technical users to benefit without complex configuration.

### Media creation tools:
- Use *mousepad* and *vim* as IDE.

<details>
<summary>Media packages</summary>

**Office:**
*LibreOffice*

**Text:**
*mousepad, vim*


**Image:**
*GIMP, InkScape*

**Video:**
*OpenShot*

**Audio:**
*Audacity*

</details>

### Internet & AI:
- *Tor browser*
- **[Fenyx browser](https://github.com/flaxware/fenyx)**
- **[Flaxy Fenyx AI](https://github.com/flaxware/flaxy.fenyx.ai)**

---
## Efficient:
### Stability:
Built to ensure reliability and stability, long-term support while giving rapid fixed releases, and access to a mature open-source software ecosystem.

### Hardware support:
We try to support old hardware very well, make old modern new.

---
## Perfect:
Our system is a perfect set up with efficient solutions.
### User interface:
**[FlaXFce-trinity](https://github.com/flaxware/flaxfce-trinity)** - *xfce* enhance by configuration and *aqua* theming , *xfce* by itself is designed to embody traditional Unix philosophy of modularity and reusability includes:
- Theme
- UI configuration

### System hardening:
- Configured ready to go UI.
- Hardened kernel configuration and secure system defaults.
- Strict permission models and reduced attack surface.

## Flexible:
### Multi-Kernel architecture:
[Flax is modular and hierarchical system.](https://github.com/flaxware/flax.system/#portable)
- This subsystem may be used for specialized networking and isolation function.
- Subsystem running in VM/Container while sharing communication layer.
- Kernel module for communication layer and kernel control.
- Multi-kernel can be used as a microkernel.
- Microkernel can be used for networking stack, which is used as a Whonix-style gateway model.

### Windows compatibility layer:
Flax OS allows to run windows executables using Wine, Proton and dedicated technologies.
- *Q4Wine* as GUI for Wine

### Registry:
Registry directory is */etc*
Can be edited using Bash scripting language, contains all system settings.

### Packaging:
- **[superpkg / xpkg](https://github.com/flaxware/superpkg.xpkg)**
- *apt*
- *.deb* with *gdebi*
- *Synaptic*
- *GNOME software store*

## Portable:
Flax is a highly modular system with hierarchy, software repositories separate it's components into multiple packages.
### Modularity:
We are putting effort into making components reusable on other systems.

### Hierarchy:
File systems and repositories are made in tree-like architecture.

### Live boot:
- Live-session workflows similar to Tails.
- Optional non-persistent modes to avoid long-term data retention, persistent mode can be achived through FlaxBox.
- Reduced forensic footprint through ephemeral system states, full RAM erasement.

---
## Safe:
- [Offense🔴](https://github.com/flaxware/flax.system/#offense)
- [Defense🔵](https://github.com/flaxware/flax.system/#defense)
> We offer both, real security comes from understanding both sides.
*One of the reasons why our logo is purple*

### Offense:
Offensive security tools inspired by:
- Kali Linux — Metasploit, NMap, aircrack-ng and other tools.
- Black Arch — dedicated security tools.

### Defense:
### Security-first design:
In the Unix security model, a user may own files and directories.
Designed to minimize data leakage through hardened defaults, secure networking, and strong encryption. Integrates concepts and technologies inspired by:
- Qubes OS — compartmentalization and workload isolation.
- Tails — live OS and non-persistent privacy workflows.
- Whonix — Tor-based network isolation via a dedicated gateway. 
- Kodachi — curated security and anonymity tools.
- Parrot OS — Ingognito mode.

## Security architecture:
Flax OS follows a defense-in-depth security model, layering multiple protections to reduce attack surfaces and limit the impact of potential compromises.

---
### Security & privacy tooling:
- **[FlaxDefender](https://github.com/flaxware/flaxdefender)**
> Centralized security center, through there you can control firewall rules, Tor routing, metadata cleaning, system monitoring, anti-virus and so on.
- Full-disk encryption and encrypted user data by default.
- Modern cryptographic standards for storage and communication.
- Secure credential and key management practices.
---
- **[FlaxBox](https://github.com/flaxware/flaxbox)**
> Envisioned for managing encrypted, isolated environments such and user data. A Knox-like technology, allows users to manage security-related components such as containers and virtual machines, can be injected with USB or just kept on a computer, the container is fully encyptable, after you eject a box, the RAM block of box itself gets erased.
- Application and service isolation inspired by Qubes OS and Knox principles.
- Use of containers, sandboxes, and Linux namespaces.
- Least-privilege execution to prevent lateral movement.
- Pre-installed and curated security tools inspired by Kodachi.
- Encryption utilities for data at rest and in transit.
---
- **[FlaxNet](https://github.com/flaxware/flaxnet)**
> Tor, VPN, Proxy, Torrent and full gateway technology.
- Optional Whonix gateway architecture to isolate network traffic.
- Tor-based routing for anonymized connections.
- Firewall-enforced separation between applications and the network.
- DNS leak prevention and traffic filtering.
- Pentesting tools within system by default, not all but basic ones yes, if you want a full bundle write install the following: "sudo superpkg install flax-pentest".
- Clear security states and configurable privacy modes.
- Balanced automation to prevent misconfiguration.
- Security features designed to be understandable and controllable.

---
## Philosophy:
Flax system is god's third temple rebuild from ashes (Temple OS reference). Unix philosophy implementation.
The idea for [ideals](https://github.com/flaxware/flax.system#ideals) comes from C++;
- The use of plain text for storing data;
- Hierarchical file system;

### Standard X:
In ancient Unix the *sticky bit* (octal 1000) now has a holdover in Flax, it was possible (in ancient Unix) to mark executable file "not swapable", kernel ignores the *sticky bit*, but if applied to directory, it prevents flexible users from deleting or renaming files; Using *ps* options without the leading dash invokes the command with "BSD style" behavior. The Linux version of the *ps* program found in several different Unix implementations; *top* is better than the graphical versions or *htop* because it is faster than and it consumes far less system resources. After all our monitor program shouldn't be the source of shutdown we are trying to find, that's why we didn't include *htop* but we still included *xfce4-taskmanager* for Windows familiar users; The way to learn our system is by tweaking and overstanding its security; We try to keep Flax sys "Unixy" while allowing it to mutate;

### Special keys:
- **Super key** instead of Win key.
- **Menu key** is language switching key.
- **Meta key** is name for right Alt; We kept name due to historical reasons.
- **Uni key** is name for right Ctrl key; Keeps the screen awake until you press it again.

---
## Project goals:
- Deliver a secure-by-default hybrid of UNIX and Unix-like standarts.
- Make advanced cybersecurity concepts accessible to a wider audience.
- Provide a reliable platform for secure computing and everyday use.

---
## Target audience:
- Privacy-conscious users.
- Security and Unix developers and researchers.
- Everyday users.
- Users seeking a hardened Linux desktop for daily use.
- Linux and Unix users.

## Contributing:
Contributions, suggestions, bug and vulnerability feedbacks are welcome.
Please open issues for bugs, vulnerabilities and submit pull requests to help improve Flax OS.
