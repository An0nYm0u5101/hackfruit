---
title: Dirb
desc: Scans web contents.
tags: [ActiveRecon, DirectoryDiscovery, Linux]
alts: [Gobuster, Ffuf]
website:
---

```sh
dirb http://10.0.0.1/
```

## Using SecLists

```sh
dirb https://10.0.0.1/ /usr/share/seclists/Discovery/Web-Content/common.txt
```

Reference:
<a href="https://github.com/danielmiessler/SecLists" target="_blank" rel="noopener noreferrer">
    https://github.com/danielmiessler/SecLists
</a>