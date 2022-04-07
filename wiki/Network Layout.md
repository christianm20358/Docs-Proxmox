<div id="top"></div>

<!--
    Wiki page to document current network layout.
-->

## Ideal Network Layout

This is the end goal setup for the network, at least the parts of the network dedicated to the web host. Setting up network administration servers and devices such as setting up a Domain Controller, DNS, or DHCP will be covered in another article.

## Logical Network Map

<div align="center">
  <a href="https://github.com/bidduam/Docs-Proxmox">
    <img src="images/network map.png" alt="Network Map" width="800" height="330">
  </a>
</div>

<!-- Timeline -->
## Timeline

- [x] Set up Proxmox Server
- [X] Harden device that will be used as the web server.
- [ ] Set up VLANs for network separation
- [ ] Set up Virt. Firewalls
- [ ] Set up Virt. Nginx Proxy Server
- [ ] Set up Virt. Database Server
- [ ] Set up Virt. Web Data Server

<!-- Web Server Hardening -->

## Hardening the Web Server

This device is running on Debian, so general hardening practices were applied. The root user was disabled, all admin accounts require a password to use sudo privileges, and unnecessary services were uninstalled. The SSH default port was also moved. The attack surface should now be minimal, with only two ports open. There should be no direct access from web clients as it will be managed by the reverse proxy. On internal networks the only access method is ssh.

## Network Separation

To further secure my network as well as improve performance, I will be creating multiple VLANs for network segmentation. There will be a separate VLAN for:
    - Non-Production VMs
    - Production VMs
    - Network Administration devices
