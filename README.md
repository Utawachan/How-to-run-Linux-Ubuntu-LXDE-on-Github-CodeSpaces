# How-to-run-Linux-Ubuntu-LXDE-on-Github-CodeSpaces

Step 1: create a private repository to create codespaces for it.

Step 2: run the following command in the terminal of codespaces

# docker run -p 8080:80 -e RESOLUTION=1280x720 -v /dev/shm:/dev/shm dorowu/ubuntu-desktop-lxde-vnc:latest

Step 3: Once done, there will be a running port, go to that port page to access the virtual machine

Step 4: In the settings of the web, set it to Local Scaling and full screen, rotate your phone device to landscape.

Step 5: Enter the following command into the Terminal of the virtual machine to be able to use it normally

# sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 4EB27DB2A3B88B8B

# ENJOY!!
