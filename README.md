# fully open-source wireguard VPN providers

actual "open-source" clients and providers for wireguard VPN

## fully open-source

provider | client | eur/year | eur/month | provider location
--|--|--|--|--
[privateinternetaccess.com](https://www.privateinternetaccess.com/buy-vpn-online) | [pia-foss/manual-connections](https://github.com/pia-foss/manual-connections) | 37.19 | 3.10 | USA
privateinternetaccess.com 3-year plan | | 23.33 | 1.80 |
[protonvpn.com](https://protonvpn.com/pricing/) | [ProtonVPN/linux-cli](https://github.com/ProtonVPN/linux-cli) | 60 | 5 | Switzerland

note: provider location != server location. usually, you can choose the server location = jurisdiction

## private server

alternative to open-source VPN providers

1. rent a VPS server (DigitalOcean, Linode, Vultr, Lightsail, ...)
   - https://duckduckgo.com/?q=cheap+vps+provider+for+vpn+server
2. install wireguard-server
3. connect with your wireguard-client

pro: cheap, choose any jurisdiction, use server for any purpose

con: setup is more work

criteria:

- cheap traffic
- fast connection
- server location = jurisdiction

## closed-source

provider | client | eur/year | eur/month | provider location | notes
--|--|--|--|--|--
[expressvpn.com](https://www.expressvpn.com/) | [closed-source app](https://www.expressvpn.com/vpn-software/vpn-linux) | ? | ? | British Virgin Islands | [core is open-source](https://github.com/expressvpn/lightway-core)
[nordvpn.com](https://nordvpn.com/pricing/deal-site/) | [closed-source app](https://nordvpn.com/download/linux/) | 60 | 5 | Panama
nordvpn.com 2-year plan | | 42 | 3.50 | |


## related

- https://fosspost.org/linux-vpn-clients-providers/
