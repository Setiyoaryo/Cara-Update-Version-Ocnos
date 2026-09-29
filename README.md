# Cara-Update-Version-Ocnos
# Upgrade/Downgrade OcNOS:
-------------------------------------
- Download OcNOS installer

- Upload OcNOS installer to the router in directory /home/ocnos via SFTP/SCP

- Check the downloaded OcNOS installer filesize. Make sure it has same filesize with the file on Flexnet.

> enable
# pwd
# ls -l

- Check version and license
# sh version
# sh license

- Update OcNOS: 
OcNOS# sys-update install file:///home/ocnos/OcNOS-SP-MPLS-Q2-7.0.2-9-MR-installer

- Reboot device

- Check version and license
# sh version
# sh license
