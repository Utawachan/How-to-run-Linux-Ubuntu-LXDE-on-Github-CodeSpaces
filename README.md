# How-to-run-Linux-Ubuntu-LXDE-on-Github-CodeSpaces

Step 1: create a private repository to create codespaces for it.

Step 2: run the following command in the terminal of codespaces
docker run -p 4000:80 -e RESOLUTION=1080x1920 -v /dev/shm:/dev/shm dorowu/ubuntu-desktop-lxde-vnc:latest
