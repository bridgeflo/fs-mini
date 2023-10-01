---
title: "Raspi"
date: 2022-03-20T09:36:49+01:00
draft: false
---

Eintrag in der /etc/fstab:

    192.168.178.27 raspi

    ED25519 key fingerprint is SHA256:9EGlBMnSfJjKBs8+QC6luGa5oFE7Mv7G19E8ggzWq8k

    sudo apt install git

    mkdir Downloads
    cd Downloads
    git clone https://github.com/novaspirit/pi-hosted
    cd pi-hosted
    ./install_docker
    ./install_portainer

Open: raspi:9000

Create user:
admin (raspberry)

