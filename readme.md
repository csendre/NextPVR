This is an Unraid docker template for NextPVR server with HD Homerun tuner

Usage:
- copy my_NextPVR.xml to you flash drive's /config/plugins/dockerMan/templates-user folder
- go to Docker tab and create container using the NextPVR template

If you are using a PCIe tuner card, edit my-NextPVR.xml and add --device=/dev/dvb to Extra Parameters
