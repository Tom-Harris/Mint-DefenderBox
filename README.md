# Mint-DefenderBox
Basic Mint with Security Tools

<b>It turns out the image is way too large to bring to GitHub so I uploaded it to my Google Drive and will share the link with you in a direct e-mail.   </b>

In the end though, it is a virtual machine implementing Linux Mint with some productivity and entertainment applications removed and some security tools addded.  We can use it to build monthly challenges so we can play around with security technology in a sandbox.

I intend for us to create scripts to update this base image for routine use and at some cadence will re-release the as-built image to allow members to download and be prodcutive faster (versus download an old image and update to the current workstation).  In order to use the VM you will need VMWare Workstation.

OPTION 2: Roll your own

Grab a copy of your favorite Linux distro.  I usually use Debian-based distro's to keep it simple.  Load either VMWare Player or VirtualBox to your workstation then use that to load a Linux VM.  Once the image is running and patched run follow these instructions to load Wireshark: https://techviewleo.com/how-to-install-wireshark-on-linux-mint/

I dont't see where they added the user to the Wireshark group so if you run into permissions issues, run this command:

sudo usermod -a -G wireshark $USER     # change $USER to the account you will use for wireshark

Once you have the base image built go to the challenges folder and grab the instructions to prepare for the week.



