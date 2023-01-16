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

traffic is the main bottleneck

- https://duckduckgo.com/?q=vps+bittorrent+seedbox+providers+2022
  - https://www.seedboxexpert.com/seedbox-guide/
  - https://seedboxgui.de/seedbox/
    - https://snthostings.com/seedbox/100mbps-seedbox/ office location: India
  - https://greycoder.com/best-seedbox/
- https://seedit4.me/ NL
   - Sidekick Pro: 1.5 TB disk, 5 TB traffic/month (public trackers allowed), 12 eur/month, 1 Gbps link
   - Hero Pro: 2 TB disk, 9 TB traffic/month (public trackers allowed), 18 eur/month, 1 Gbps link
   - Super Hero Pro: 3 TB disk, 15 TB traffic/month (public trackers allowed), 24 eur/month, 1 Gbps link
   - Avenger Pro: 5 TB disk, 25 TB traffic/month (public trackers allowed), 40 eur/month, 1 Gbps link
- https://ultra.cc/#plan-pricing NL
  - Eagle: 3 TB disk, 6 TB traffic/month, 12 eur/month, shared 50 Gbps link
- https://www.seedhost.eu/seedboxes.php NL
  - SDATA: 4 TB disk, 9 TB traffic/month, 12 eur/month, 120 eur/year, 1 Gbps link
  - SDATA L: 8 TB disk, 16 TB traffic/month, 19 eur/month, 190 eur/year, 1 Gbps link
- https://dediseedbox.com/vps.html NL
   - 0.750 TB disk, 10 TB traffic/month, 15 usd/month, 10 Gbps link
   - 1 TB disk, 14 TB traffic/month, 20 usd/month, 10 Gbps link
   - 1.5 TB disk, 18 TB traffic/month, 25 usd/month, 10 Gbps link
- https://evoseedbox.com/
   - Speed: 0.300 TB disk, 4 TB traffic/month, 12 eur/month, 0.1 Gbps link
   - Blaze: 0.600 TB disk, 7 TB traffic/month, 18 eur/month, 0.1 Gbps link

### unlimited traffic

"unlimited" ... but these servers have other limits

<details>

- https://www.rapidseedbox.com/#pricing NL/FR
   - Fast: 1.2 TB disk, unlimited traffic, 18 eur/month, 1 Gbps link
- https://xirvik.com/seedboxes/plan/29-shared-servers NL/UK/US (?)
  - Feast: 0.5 TB disk, unlimited traffic, 13 usd/month, 2 Gbps link
  - Ratio: 1 TB disk, unlimited traffic, 20 usd/month, 2 Gbps link
- https://www.feralhosting.com/pricing UK?
  - Helium: 1 TB disk, unlimited traffic, 10 gbp/month, 20 Gbps link
  - Neon: 1.5 TB disk, unlimited traffic, 15 gbp/month, 20 Gbps link
  - Argon: 2 TB disk, unlimited traffic, 20 gbp/month, 20 Gbps link
- https://bigsb.net/plans/
   - Baby Box 130: 0.130 TB disk, unlimited traffic, 12 eur/month, 0.1 Gbps link
   - Baby Box 260: 0.260 TB disk, unlimited traffic, 18 eur/month, 0.1 Gbps link

</details>

### limitations

#### limited seeding to public trackers or DHT

- https://www.reddit.com/r/seedboxes/comments/7nwuz4/best_seedbox_for_public_torrents/
- https://dediseedbox.com/wiki/knowledgebase/do-you-allow-public-trackers/
   - Q: Do you allow public trackers? - A: We allow downloading from public trackers but uploading/seeding to public trackers is not possible.
- https://cheapseedboxes.com/seedboxes-that-support-public-trackers/
   - [Sdedi.com](https://www.sdedi.com/) FR
   - [useed.fr](https://www.useed.fr/) FR
   - [feralhosting.com](https://www.feralhosting.com/pricing) UK
   - [darkseed.fr](https://darkseed.fr/) FR
   - [ma-seedbox.me](https://ma-seedbox.me/) FR
   - [seedbox.fr](https://www.seedbox.fr/) FR
- https://www.reddit.com/r/seedboxes/comments/skfomh/seedboxes_and_public_trackers/
   - It really depends on the provider. I use ultra.cc and they don’t seem to give a crap as they as their business is based in Singapore with the servers in the Netherlands, they are practically immune to DMCA although they do have a policy that recommends that you only seed public tracker torrents to 2 ratio. It’s only a recommendation though.
- https://www.reddit.com/r/seedboxes/comments/a7jcvf/public_trackers_allowed/
- https://xirvik.com/seedboxes/plan/29-shared-servers
   - Public trackers: OK to download, but seed only to reasonable ratios
   - Torrents in public trackers don't have a short traffic peak like those in private trackers. **A popular torrent in a public tracker can consume terabytes of traffic** every day for months, starving other torrents and increasing server load (which affects all users), cost, etc. There's also no need to seed forever in public tracker - with the amount of users, torrents stay healthy for years without anyone having to accept the responsibility of keeping them alive.

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

## traffic

factor = 1/8/1E6\*3600\*24\*30 = 0.324 TB / (MBit/s)

uplink | upload traffic/month
-- | --
10 MBit/s | 3 TB
40 MBit/s | 13 TB
100 MBit/s | 30 TB
1 GBit/s | 300 TB
10 GBit/s | 3000 TB

## related

- https://fosspost.org/linux-vpn-clients-providers/
