# Packer ubuntu (22.0.4) image builder 
## This repository contains Packer files to build Ubuntu images for my personal infrastructure on Vsphere 7.
## Ubuntu Server 22.04 (ubuntu-22.04) based on autoinstalls using cloud-init.

Feel free to fork or edit what you need.
You can clone it and change the variable file and run the bellowing command:

build -force -on-error=ask -var-file variables.json ubuntu-22.04-live-server-packer.json
