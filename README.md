# Ansible Role: wireguard

# Disclaimer

I couldn't be responsible with any production issues if you use this role without any prior tests.  
This role is designed for my proper environment and possibly not correspond to your.

The master branch is development branch. Use only release/* branches for production.

# Introduction

This role is designed to perform wireguard server installation on GNU/Linux hosts.  
It’ll generate automatically peers configuration with or without mesh hability.

# Supported OS

**Debian** :
- buster (10)
- bullseye (11)

**Ubuntu** :
- Bionic Beaver (18.04) - ESS : 04/2023 / EOL : 04/2028
- Focal Fossa (20.04) - ESS : 04/2025 / EOL : 04/2030
- Hirsute Hippo (21.04) - ESS : 01/2022 / EOL : 01/2022

**Rocky** :
- 8

# Requirements

## On target OS

You need to have python3 package installed on remote OS to use this role.

# Changelog

To clearest and updated changelog, I encourage you to see pull requests with flags "feature".

# Roadmap

You could refer to milestones to full current roadmap.

### v1.0.0

- Install and configure wireguard on following OS :
  - Debian 10
  - Debian 11
  - Rocky 8
  - Ubuntu 18.04
  - Ubuntu 20.04
  - Ubuntu 21.04
