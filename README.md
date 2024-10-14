<h1 style="text-align: center;">nerm<sub>.al</sub> </h1>
<p style="text-align: center;"><b>homelab running frontend media applications,<br>minecraft servers, a gitea instance... etc </b></p>
<p style="text-align: center;"><i>still an early wip</i></p>

## Overview   
> Each folder in this repo represents a seperate proxmox container and contains the applicable docker-compose stack.

**Rack layout** <br>
power strip <br>
OPNSense box <br>
MikroTik switch <br>
gaming PC <br>
proxmox host <br>

### Proxmox hosts
> [!NOTE]
> For more information check the wiki
#### [Frontend](frontend/README.md)
| LXC - Arch|
| :-: |
| [Jellyfin](https://github.com/jellyfin/jellyfin), [Kavita](https://github.com/Kareadita/Kavita) |
| [Gitea](https://github.com/go-gitea/gitea), [Vaultarden](https://github.com/dani-garcia/vaultwarden) | 
| [Authentik](https://github.com/goauthentik/authentik) |

#### [Backend](backend/README.md)
| LXC - Arch|
| :-: |
| [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager) |
| [Grafana](https://github.com/grafana/grafana), [Loki](https://github.com/grafana/loki), [Promtail](https://github.com/grafana/promtail) |
| [Gluetun](https://github.com/qdm12/gluetun), [qBittorrent](https://github.com/qbittorrent/qBittorrent), [SABnzbd](https://github.com/sabnzbd/sabnzbd) |
| [Sonarr](https://github.com/Sonarr/Sonarr), [Radarr](https://github.com/Radarr/Radarr), [Prowlarr](https://github.com/Prowlarr/Prowlarr), [Bazarr](https://github.com/morpheus65535/bazarr), [Doplarr](https://github.com/kiranshila/Doplarr) |

#### [Server](servers/README.md)
| LXC - Arch|
| :-: |
| [Velocity](https://github.com/PaperMC/Velocity), [Paper](https://github.com/PaperMC/Paper), [Forge](https://github.com/MinecraftForge/MinecraftForge) |

#### Nas
| VM |
| :-: |
| [TrueNAS Scale](https://github.com/truenas/scale-build) |
