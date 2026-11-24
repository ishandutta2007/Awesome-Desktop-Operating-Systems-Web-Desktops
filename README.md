# Awesome-Desktop-Operating-Systems-Web-Desktops

# Top Desktop Operating Systems & Web Desktops Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Browser-Based Web Desktops, Containerized Remote Desktops, Cloud VDI Workspaces, HTML5/WebAssembly OS Environments & Desktop-as-a-Service (DaaS)*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Desktop Operating Systems & Web Desktops**. These tools stream, emulate, containerize, and render full graphical desktop operating systems and interactive web-native desktop environments directly inside web browsers across Docker servers, cloud VDI infrastructure, homelabs, and WebAssembly sandboxes.

**Examples** include WebTop, Kasm Workspaces, LinuxServer.io Cloud, DaedalOS, Windows 365, Amazon WorkSpaces, Paperspace Core, AppOnFly, Dizzion Frame, OS.js Cloud, and PhreshOS/system (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for browser-native Web Desktops & OS simulations (`PhreshOS/system`, `DaedalOS`, `OS.js`, `Puter`, `Win11React`, `DustinBrett/daedalOS`), containerized Linux remote desktops (`LinuxServer.io Webtop`, `Kasm Workspaces Community`, `Neko`), and clientless HTML5 remote desktop gateways (`Apache Guacamole`, `noVNC`, `XPRA`) — ideal for homelab self-hosters, remote engineering teams, educators, and creative web OS builders.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Windows 365 (Microsoft Cloud PC)](https://microsoft.com)**  
  Managed cloud Desktop-as-a-Service (DaaS) streaming persistent personalized Windows 11 desktop environments to any browser, tablet, or thin client.

- **[Amazon WorkSpaces](https://amazon.com)**  
  Fully managed, persistent cloud virtual desktop service on AWS supporting Windows, Ubuntu, and Amazon Linux workspaces with enterprise Active Directory integration.

- **[Kasm Workspaces Cloud / Enterprise](https://kasmweb.com)**  
  Containerized Desktop Infrastructure (CDI) and browser-isolation streaming platform delivering on-demand disposable Linux/Windows desktops and browser sandboxes.

- **[Dizzion Frame (formerly Nutanix / Xi Frame)](https://dizzion.com)**  
  Cloud-native Desktop-as-a-Service platform streaming GPU-accelerated Windows and Linux desktop applications directly to HTML5 browsers with zero plugins.

- **[Paperspace Core (DigitalOcean)](https://paperspace.com)**  
  Cloud virtual desktop and GPU workstation infrastructure offering low-latency browser streaming for 3D rendering, CAD, AI development, and remote studios.

- **[AppOnFly](https://apponfly.com)**  
  Instant cloud Windows VPS and remote desktop service accessible directly from any web browser or RDP client within seconds.

- **[Shells.com](https://shells.com)**  
  Personal cloud desktop service providing pre-configured Ubuntu, Debian, Fedora, and Windows virtual desktops accessible from smartphones, Chromebooks, and browsers.

- **[Neverinstall](https://neverinstall.com)**  
  Cloud personal computer and browser-streamed Linux/Windows workspace platform enabling instant access to desktop IDEs, browsers, and creative apps.

- **[OS.js Cloud & Hosted Web Desktop Suites](https://os-js.org)**  
  Managed cloud hosting and enterprise integrations built around open-source web desktop frameworks for white-label browser workspaces.


## Open-Source GitHub Projects

- **[PhreshOS/system](https://github.com)**  
  Open-source web desktop and operating system environment engineered for clean, responsive browser-based desktop UX, window management, and modular web apps.

- **[LinuxServer.io Webtop (`linuxserver/docker-webtop`)](https://github.com)**  
  Flagship open-source Docker container suite delivering full Ubuntu, Alpine, Fedora, Arch, and Debian desktop environments (XFCE, KDE, MATE, i3) directly to your browser via Selkies/KasmVNC.

- **[DaedalOS (`DustinBrett/daedalOS`)](https://github.com)**  
  Remarkable open-source desktop environment running completely client-side in the browser with window management, file explorer, x86/DOS/WebAssembly emulators, Doom, and terminal apps.

- **[Puter (`HeyPuter/puter`)](https://github.com)**  
  Feature-rich, self-hostable open-source Internet OS and web desktop environment written in JavaScript featuring cloud storage, window manager, code editor, and app ecosystem.

- **[OS.js (`os-js/OS.js`)](https://github.com)**  
  Extensible open-source JavaScript web desktop platform providing a full window manager, virtual filesystem adapters (WebDAV, S3, local), authentication, and application SDK.

- **[Apache Guacamole (`apache/guacamole-client` & `guacamole-server`)](https://github.com)**  
  Industry-standard open-source clientless remote desktop gateway supporting VNC, RDP, and SSH directly inside HTML5 web browsers with zero client plugins required.

- **[KasmVNC (`kasmtech/KasmVNC`)](https://github.com)**  
  Modern, high-FPS open-source VNC server engineered for browser streaming with WebP/QOI dynamic encoding, WebRTC/WebSocket transport, clipboard sync, and audio pass-through.

- **[noVNC (`novnc/noVNC`)](https://github.com)**  
  Foundational open-source HTML5 VNC client library and web application powering browser console access across Proxmox, OpenStack, QEMU/KVM, and Docker containers.

- **[Neko (`m1k1o/neko`)](https://github.com)**  
  Self-hosted open-source virtual browser and desktop container powered by WebRTC enabling low-latency multiplayer screen sharing and collaborative browsing inside Docker.

- **[Xpra (`Xpra-org/xpra`)](https://github.com)**  
  Versatile open-source "screen for X" multi-platform remote display server allowing individual Linux/Windows GUI applications or full desktops to stream seamlessly over HTML5/WebSockets.

- **[Win11React (`blueedgetechno/win11React`) & WebVM (`leaningtech/webvm`)](https://github.com)**  
  Popular open-source browser OS projects combining faithful web desktop UI recreation (`Win11React`) and full client-side Linux x86 virtualization via WebAssembly (`WebVM` / CheerpX).

### Additional Strong Open-Source Options

- **[Selkies-GStreamer (`selkies-project/selkies-gstreamer`)](https://github.com)** for ultra-low-latency, GPU-accelerated (NVENC/VAAPI) WebRTC Linux desktop streaming inside Kubernetes and Docker containers.
- **[v86 (`copy/v86`)](https://github.com)** for an open-source x86 PC emulator compiled to WebAssembly capable of booting Linux, Windows 98, ReactOS, KolibriOS, and FreeDOS right in a browser tab.
- **[Sunshine (`LizardByte/Sunshine`) & Moonlight (`moonlight-stream/moonlight-qt`)](https://github.com)** for self-hosted, open-source low-latency desktop and gaming streaming at up to 4K/120fps HDR across devices.
- **[dockur/windows (`dockur/windows`) & dockur/macos (`dockur/macos`)](https://github.com)** for automated, KVM-accelerated Windows and macOS virtual machines running inside Docker with built-in web-browser desktop viewers.
- **[Nextcloud (`nextcloud/server`)](https://github.com)** for a self-hosted open-source web workspace uniting files, Collabora/OnlyOffice apps, calendar, and communication in a browser hub.

**Frameworks for building custom systems**: Combine **LinuxServer.io Webtop** or **Selkies-GStreamer** for containerized Linux browser desktops, **Apache Guacamole** for multi-protocol HTML5 RDP/VNC/SSH access, and **PhreshOS/system**, **Puter**, or **OS.js** for pure browser-native web desktop environments.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Self-hosted web desktops (`Webtop`, `Guacamole`, `Puter`, `dockur/windows`) grant full interactive desktop and shell access through a browser; always deploy behind HTTPS/TLS reverse proxies, strong OIDC/MFA authentication, and VPN/Zero-Trust network controls.
- Note that `Kasm Workspaces` uses an open-core model (offering a free Community Edition alongside commercial Enterprise tiers), while `LinuxServer.io Webtop`, `Apache Guacamole`, `noVNC`, `DaedalOS`, and `OS.js` are fully open-source.

---

**Made for homelab self-hosters, remote engineering teams, educators, web OS creators, and open-source contributors.**  
Let's make desktop operating systems and web desktops more open, portable, and accessible from any browser.
