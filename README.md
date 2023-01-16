# fully open-source wireguard VPN providers

actual "open-source" clients and providers for wireguard VPN

## fully open-source VPN clients

provider | client | eur/year | eur/month | provider location
--|--|--|--|--
[privateinternetaccess.com](https://www.privateinternetaccess.com/buy-vpn-online) | [pia-foss/manual-connections](https://github.com/pia-foss/manual-connections) | 37.19 | 3.10 | USA
privateinternetaccess.com 3-year plan | | 23.33 | 1.80 |
[protonvpn.com](https://protonvpn.com/pricing/) | [ProtonVPN/linux-cli](https://github.com/ProtonVPN/linux-cli) | 60 | 5 | Switzerland

note: provider location != server location. usually, you can choose the server location = jurisdiction

## private server

alternative to open-source VPN providers

1. rent a VPS server (DigitalOcean, Linode, Vultr, Lightsail, ...)
  - https://duckduckgo.com/?q=cheap+vps+provider+for+wireguard+vpn+server
2. install wireguard-server
3. connect with your wireguard-client

pro: cheap, choose any jurisdiction, use server for any purpose

con: setup is more work, server location is less flexible

criteria:

- cheap traffic
- fast connection
- server location = jurisdiction

## seedbox

alternative to private server

no root access

- https://duckduckgo.com/?q=vps+bittorrent+seedbox+providers+2022
  - https://www.seedboxexpert.com/seedbox-guide/
    - https://ultra.cc/#plan-pricing NL
    - https://www.rapidseedbox.com/#pricing
  - https://seedboxgui.de/seedbox/
    - https://dediseedbox.com/dedicated.html NL
    - https://seedit4.me/ NL
    - https://evoseedbox.com/
    - https://snthostings.com/seedbox/100mbps-seedbox/
    - https://bigsb.net/plans/
  - https://greycoder.com/best-seedbox/

## closed-source VPN clients

provider | client | eur/year | eur/month | provider location | notes
--|--|--|--|--|--
[expressvpn.com](https://www.expressvpn.com/) | [closed-source app](https://www.expressvpn.com/vpn-software/vpn-linux) | ? | ? | British Virgin Islands | [core is open-source](https://github.com/expressvpn/lightway-core)
[nordvpn.com](https://nordvpn.com/pricing/deal-site/) | [closed-source app](https://nordvpn.com/download/linux/) | 60 | 5 | Panama
nordvpn.com 2-year plan | | 42 | 3.50 | |

## server location

should be near your location = low latency = low ping

- 🟢 Downloading allowed (for personal use): Poland, Spain, Switzerland
- 🟡 Download Fines (not enforced): Argentina, Australia, Brazil, Canada, China, Colombia, Czech Republic, Denmark, Egypt, Greece, Iran, Israel, Italy, Latvia, Mexico, The Netherlands, Philippines, Portugal, Romania, Russia Singapore, Slovakia, Slovenia, South Africa, Uruguay
- 🔴 Download fines (enforced): Belgium, Finland, France, Germany, India, Japan, Malaysia, New Zealand, United Arab Emirates, United Kingdom, United States

based on

- https://vpnoverview.com/privacy/downloading/download-fines/
- https://www.vpnmentor.com/blog/torrents-illegal-update-country/
- https://vpnpro.com/blog/is-torrenting-illegal/

## related

- https://fosspost.org/linux-vpn-clients-providers/
