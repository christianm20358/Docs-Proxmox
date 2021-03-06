<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/christianm20358/Docs-Proxmox">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Proxmox Server Documentation</h3>

  <p align="center">
    Documenting the setup and progress of the Proxmox server for a small network.
    <br />
    <a href="https://github.com/christianm20358/Docs-Proxmox/wiki"><strong>Explore the docs »</strong></a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository is for documentation of my home lab. The primary focus will be on Cybersecurity. The goal at the end of the project is to harden a small LAN according to the CIS 18 framework. The main interface server handling the majority of the network administration is a dedicated server installed with Proxmox, a debian based virtual environment that is ideal for managing multiple virtual machines and can also contain docker images. Some combination of the two will likely perform most of the network management.

Here's why:

* I believe in learning by doing. I would like to implement security controls on my network that don't impact usability but improve security.
* I want to find or create tools that I would want to use myself, not only to improve security, but also to improve quality of life for network users.
* You should implement DRY principles to the rest of your life :smile:

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

These are the primary tools utilized in the home lab. Individual Docker containers or VM Images are listed in the Acknowledgments section.

* [Proxmox VE](https://www.proxmox.com/en/proxmox-ve/)
* [Docker](https://www.docker.com/)
* [Debian 11](https://www.debian.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

## Main Server Resource Usage

<div align="center">
  <a href="https://github.com/christianm20358/Docs-Proxmox">
    <img src="images/screenshot.png" alt="Screenshot" width="800" height="330">
  </a>
</div>

_For more examples, please refer to the [Documentation](https://github.com/christianm20358/Docs-Proxmox/wiki)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- Timeline -->
## Timeline

- [x] Debian Container Hardening - 4-5-22
- [x] Added Kanban List - 4-5-22
- [X] Set up Authentication Server
- [ ] Set up Reverse Proxy
- [ ] Add VPN Tunnel

_For a more complete timeline, please refer to the [Kanban](https://github.com/christianm20358/Docs-Proxmox/projects/1)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Christian Miller - [LinkedIn](https://www.linkedin.com/in/christian-miller-266684168/) - christianm20358@gmail.com

Project Link: [https://github.com/christianm20358/Docs-Proxmox](https://github.com/christianm20358/Docs-Proxmox)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

I wanted to acknowledge the invaluable assistance received from these resources. The open source community makes this kind of project possible, as well as various content creator guides. I also want to share my appreciation for my colleagues for their advice and for sharing their knowledge along the way.

* [Josh Guttormsen](https://www.linkedin.com/in/josh-guttormsen/)
* [Justin Davis](https://www.linkedin.com/in/justin-davis-787b7b5b/)
* [Learn Linux TV - Proxmox Setup](https://www.youtube.com/channel/UCxQKHvKbmSzGMvUrVtJYnUA)
* [Stack Overflow](https://stackoverflow.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/christian-miller-266684168/
