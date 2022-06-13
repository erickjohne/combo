# combo
Simple installation Docker-CE, Docker-Compose, NGinX Proxy Manager, and Portainer-CE

Create a folder in your server / , create a new file called installation.sh copy the script into this file, 

Give the right permission to this file such as chmod +x <your-new-file>.sh
  
run the script 
  
  ./installation.sh
  
  Done, Now just select what would you like to install, 

  First, you'll be prompted to select the number for your OS / Distro. Currently I support CentOS 7 and 8, Debian 10 and 11, Ubuntu 18.04, 20.04, 21.04, and 21.10.

Next, you'll be asked to answer "y" to any of the four software packages you'd like to install.

Docker-CE
Docker-Compose
NGinx Proxy Manager
Navidrome (music player)
Speedtest (recurring internet speedtest)
Portainer-CE
if you answer y to Portainer, you'll be asked another question
Do you want full Portainer-CE with the web UI, or just Portainer-agent (which you connect to another full portainer instance).

Make that selection, and the install will continue.

Answering "n" to any of them will cause them to be skipped.
