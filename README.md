

HOW To:

1. Installiere docker und alles was dazu gehört

apt vorbereiten:
https://docs.docker.com/engine/install/debian/

   sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin git-all

1. Cole von Git
   git clone https://github.com/DdoubleU-2/DeepSeekDocker.git
   
4. Erstelle das docker Image
   
   sudo docker build immagename:imageVersion /pfadzurDatei
   
   z.B. sudo docker build deepseek7b:latest /home/daniel/GIT/DeepSeekDocker/DockerFiles/DeepSeek7B/dockerfile
   
5. Starte den Docker container
   
   sudo docker run -it deepseek7b:latest
