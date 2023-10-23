# Home NAS and VPN
A repository to hold information pertaining to a homemade Network Attached Storage (NAS) and Virtual Private Network (VPN) solution for easy remote file access.

The materials used to accomplish this project are:
<ul>
  <li>1 Raspberry Pi</li>
  <li>1 Large USB storage Device</li>
  <li>1 Wireless Router</li>
</ul>

The frameworks/codebases used for this project are:
<ul>
  <li>PIVPN - https://pivpn.io</li>
  <li>Wireguard - https://www.wireguard.com</li>
  <li>OpenMediaVault - https://www.openmediavault.org</li>
</ul>

The method that I used to set this project up correctly was using PiVPN, https://pivpn.io/#install, to install and automatically configure WireGuard for my Raspberry Pi.
After fully configuring WireGuard, I was able to follow the instructions on this repo, https://github.com/OpenMediaVault-Plugin-Developers/installScript

Finally, by adding the correct IP address on my wireless router for both port forwarding and for IP reservation, the WireGuard VPN and NAS systems were working.
I've tested this project, and it works on Linux, iOS, MacOS, Windows, and Android.

The completion of this project has allowed me to use a configurable, secure, and easily accessible storage solution.
