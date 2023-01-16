# fully open-source wireguard VPN providers

actual "open-source" clients and providers for wireguard VPN

## fully open-source wireguard VPN clients

provider | client | eur/year | eur/month | provider location
--|--|--|--|--
[privateinternetaccess.com](https://www.privateinternetaccess.com/buy-vpn-online) | [pia-foss/manual-connections](https://github.com/pia-foss/manual-connections) | 37.19 | 3.10 | USA
privateinternetaccess.com 3-year plan | | 23.33 | 1.80 |
[protonvpn.com](https://protonvpn.com/pricing/) | [ProtonVPN/linux-cli](https://github.com/ProtonVPN/linux-cli) | 60 | 5 | Switzerland

note: provider location != server location. usually, you can choose the server location = jurisdiction

## closed-source wireguard VPN clients

the wireguard protocol is open-source, see https://www.wireguard.com/repositories/

... but most providers offer only closed-source wireguard VPN clients

provider | client | eur/year | eur/month | provider location | notes
--|--|--|--|--|--
[expressvpn.com](https://www.expressvpn.com/) | [closed-source app](https://www.expressvpn.com/vpn-software/vpn-linux) | ? | ? | British Virgin Islands | [core is open-source](https://github.com/expressvpn/lightway-core)
[nordvpn.com](https://nordvpn.com/pricing/deal-site/) | [closed-source app](https://nordvpn.com/download/linux/) | 60 | 5 | Panama
nordvpn.com 2-year plan | | 42 | 3.50 | |

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

### seedbox in spain

- https://www.reddit.com/r/seedboxes/comments/32xeve/seedbox_in_spain/
- http://www.seedbox-spain.com/
- 

## server location

should be near your location = low latency = low ping

### copyright laws

- 🟢 Downloading allowed (for personal use): Poland, Spain, Switzerland
- 🟡 Download Fines (not enforced): Argentina, Australia, Brazil, Canada, China, Colombia, Czech Republic, Denmark, Egypt, Greece, Iran, Israel, Italy, Latvia, Mexico, The Netherlands, Philippines, Portugal, Romania, Russia Singapore, Slovakia, Slovenia, South Africa, Uruguay
- 🔴 Download fines (enforced): Belgium, Finland, France, Germany, India, Japan, Malaysia, New Zealand, United Arab Emirates, United Kingdom, United States

based on

- https://vpnoverview.com/privacy/downloading/download-fines/
- https://www.vpnmentor.com/blog/torrents-illegal-update-country/
- https://vpnpro.com/blog/is-torrenting-illegal/

### connectivity

should be close to internet exchange points (IXPs) (London, Frankfurt, Amsterdam, Moscow, Paris, Seattle, Los Angeles, Sao Paulo, ...)

- https://www.itgsnews.com/mapping-internet-maps/
   - https://global-internet-map-2012.telegeography.com/
- https://www.telecomramblings.com/network-maps/europe/
   - https://www.colt.net/global-network/coverage-maps/
   - https://www.gtt.net/us-en/about-us/our-network
- https://www.internetexchangemap.com/
- https://www.datacentermap.com/ixps.html
- https://en.wikipedia.org/wiki/List_of_Internet_exchange_points_by_size

### energy cost

- https://duckduckgo.com/?q=electricity+prices+by+country
- https://advisor.visualcapitalist.com/global-energy-prices-by-country/
- https://www.globalpetrolprices.com/electricity_prices/

<details>
<summary>Electricity prices for business, June 2022 (kWh, Euro)</summary>

- 🟡 Argentina 0.024
- 🟡 Egypt 0.039
- 🟡 South Africa 0.073
- 🟡 Canada 0.087
- 🟡 China 0.087
- 🟡 Russia 0.092
- 🟡 Uruguay 0.106
- 🟡 Greece 0.117
- 🟡 Colombia 0.123
- 🟡 Brazil 0.132
- 🟡 Philippines 0.132
- 🟡 Slovenia 0.132
- 🟢 Spain 0.140
- 🟡 Israel 0.154
- 🟢 Switzerland 0.164
- 🟡 Slovakia 0.170
- 🟡 Mexico 0.173
- 🟡 Romania 0.203
- 🟡 Singapore 0.217
- 🟡 Australia 0.223
- 🟢 Poland 0.251
- 🟡 Latvia 0.253
- 🟡 Portugal 0.254
- 🟡 Czech Republic 0.267
- 🟡 Denmark 0.322
- 🟡 Netherlands 0.360
- 🟡 Italy 0.390
- 🟡 Iran ?

</details>

## related

- https://fosspost.org/linux-vpn-clients-providers/
