# Bonjour-Services-list
| Service | Description |
| --- | --- |
| service ID | information |

## Proprietary

**File protocols**
| Service | Description |
| --- | --- |
| _ftp._tcp | File Transfer Protocol (FTP) |
| _http._tcp | Hypertext Transfer Protocol (HTTP) |
| _nfs._tcp | Network File System (NFS) |
| _sftp-ssh._tcp | Protocol – SFTP |
| _smb._tcp | Protocol – SMB |
| _ssh._tcp | Protocol – SSH |
| _telnet._tcp | Remote Login (TELNET) |
| _tunnel._tcp | Tunnel |
| _webdav._tcp | WebDAV File System (WEBDAV) |
| _webdav._tcp | WebDAV File System (WEBDAV) |


## Proprietary

**Android TV**
| Service | Description |
| --- | --- |
| _androidtvremote._tcp | information |

**Amazon**
| Service | Description |
| --- | --- |
| _amazonecho-remote._tcp | Amazon Echo |
| _homekit._tcp | Amazon Echo |
| _workstation._tcp | Amazon Echo |
| _amzn-wplay._tcp | Amazon TV & devices |

**Aqara**
| Service | Description |
| --- | --- |
| _aqara-setup._tcp | information |
| _aqara._tcp | information |

**Apple**
| Service | Description |
| --- | --- |
| _adisk._tcp | Time Capsule Backups |
| _afpovertcp._tcp | AppleTalk Filing Protocol (AFP) |
| _airdrop._tcp | OSX AirDrop |
| _airplay._tcp | AirPlay - Apple TV |
| _airport._tcp | AirPort Base Station |
| *._sub._apple-mobdev2._tcp | OSX Wi-Fi Sync |
| _apple-mobdev2._tcp | OSX Wi-Fi Sync |
| _apple-sasl._tcp | Apple Password Server |
| _appletv-v2._tcp | Apple TV Home Sharing |
| _atc._tcp | Apple Shared iTunes Library |
| _companion-link._tcp | Apple TV(Airyplay) iPhone as the Remote Control |
| _daap._tcp | Digital Audio Access Protocol (DAAP) |
| _device-info._tcp | OSX Device Info |
| _distcc._tcp | Distributed Compiler |
| _dpap._tcp | Digital Photo Access Protocol (DPAP) |
| _eppc._tcp | Remote AppleEvents |
| _hap._tcp | Apple HomeKit – HomeKit Accessory Protocol |
| _homekit._tcp | Apple HomeKit |
| _home-sharing._tcp | iTunes Home Sharing |
| _ica-networking._tcp | Image Capture Sharing |
| _ichat._tcp	 |  Instant Messaging Protocol |
| _KeynoteControl._tcp | OSX Keynote |
| _keynotepair._tcp | OSX Keynote |
| _mediaremotetv._tcp | Apple TV Media Remote |
| _pdl-datastream._tcp | PDL Data Stream (Port 9100) |
| _raop._tcp | AirPlay – Remote Audio Output Protocol |
| _rfb._tcp | OSX Screen Sharing |
| _riousbprint._tcp | Remote I/O USB Printer Protocol |
| _servermgr._tcp	 |  Admin |
| _sleep-proxy._udp | Wake-on-Network / Bonjour Sleep Proxy |
| _touch-able._tcp	Apple TV Remote App (iOS devices) |
| _workstation._tcp | Workgroup Manager |

**Google**
| Service | Description |
| --- | --- |
| _googlecast._tcp | Google Cast (Chromecast) |
| _sub._googlecast._tcp | Google Cast (Chromecast) |
| _ca5e8412._sub._googlecast._tcp | Something for Netflix |
| _googlezone._tcp | Google Zone (Chromecast) |
| _physicalweb._tcp | Physical Web |

**Netflix**
| Service | Description |
| --- | --- |
| urn:mdx-netflix-com:service:target:1 | Cast |
| urn:mdx-netflix-com:service:target:0 | Cast |

**Philips Hue**
| Service | Description |
| --- | --- |
| _philipshue._tcp | information |

**Roku Media Player**
| Service | Description |
| --- | --- |
| _roku._tcp | information |
| _rsp._tcp | information |

**Spotify**
| Service | Description |
| --- | --- |
| _spotify-connect._tcp | Spotify Connect  |

**Other sound systems**
| Service | Description |
| --- | --- |
| _sonos._tcp | Sonos |
| _bose._tcp | Bose |

**Routers and modems**
| Service | Description |
| --- | --- |
| _tplink._tcp | TP-Link |

**Printers & Scanners**
| Service | Description |
| --- | --- |
| _print._sub._ipp._tcp | Printers (AirPrint) |
| _cups._sub._ipps._tcp | Printers |
| _print._sub._ipps._tcp | Printers |
| _printer._tcp | Printers – Line Printer Daemon (LPD/LPR) |
| _scanner._tcp | Scanners |

**Apps**
| Service | Description |
| --- | --- |
| _airdroid._tcp | AirDroid App |
| _sketchmirror._tcp | Sketch App |
| _bcbonjour._tcp | Sketch App |
| _cloud._tcp | Cloud by Dapile |
| _esdevice._tcp | ES File Share App |
| _esfileshare._tcp | ES File Share App |
| _hudson._tcp | Jenkins App |
| _jenkins._tcp | Jenkins App |
| _nvstream._tcp | NVIDIA Shield Game Streaming |
| _omnistate._tcp | OmniGroup (OmniGraffle and other apps) |
| _photoshopserver._tcp | Adobe Photoshop Nav |

**Other**
| Service | Description |
| --- | --- |
| _readynas._tcp | Netgear ReadyNAS |
| _teamviewer._tcp | TeamViewer |
| _udisks-ssh._tcp | Ubuntu / Raspberry Pi Advertisement |
| _androidtvremote._tcp | Nvidia Shield / Android TV |
| _ndi._tcp | NDI Discovery for video streaming discovery |
| _bp2p._tcp | ??? |
| _Friendly._sub._bp2p._tcp | ??? |
| _invoke._sub._bp2p._tcp | ??? |
| _webdav._sub._bp2p_tcp | ??? |
| _xserveraid._tcp | ??? |
| _display._tcp |  Miracast over Infrastructure (Windows) |
| Service | Description |
| Service | Description |


### References:
https://github.com/eldraco/Sapito/blob/master/mDNS-services.txt
https://jonathanmumm.com/tech-it/mdns-bonjour-bible-common-service-strings-for-various-vendors/


> [!WARNING]
> Aruba devices dont require **.local** after service ID.

> [!IMPORTANT]
> Some devices require **.local** after service ID, example: **_googlecast._tcp.local**

