# Security Onion 
## Installation PoC
VM Specs:
* 4-6 CPU
* 8GB RAM
* 

### Install Evaluation Standalone:

1. First, review the Hardware Requirements page.
2. Review the Release Notes page.
3. Download and verify our Security Onion ISO image.
4. Boot the ISO image and select the Install option.
5. Follow the prompts in the Xubuntu installer. If prompted with an encrypt home folder or encrypt partition option, DO NOT enable this feature. If asked about automatic updates, DO NOT enable automatic updates. Reboot into your new installation. Login using the username/password you specified during installation.
6. Verify that you have Internet connectivity. If necessary, configure your proxy settings.
7. Install updates and reboot.
8. Double-click the Setup icon. The Setup wizard will walk you through configuring /etc/network/interfaces and will then reboot.
9. After rebooting, log back in and start the Setup wizard again. It will detect that you have already configured /etc/network/interfaces and will walk you through the rest of the configuration. When prompted for Evaluation Mode or Production Mode, choose Evaluation Mode.
9. Once you''ve completed the Setup wizard, use the Desktop icons to login to Sguil, Squert, or ELSA.
10. Finally, review the Post Installation page.

