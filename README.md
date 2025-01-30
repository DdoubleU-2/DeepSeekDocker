

HOW To:

1. Installiere docker und alles was dazu gehört
   
   sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

   
3. Erstelle das docker Image
   
   sudo docker build immagename:imageVersion /pfadzurDatei
   
   z.B. sudo docker build deepseek7b:latest /home/daniel/GIT/DeepSeekDocker/DockerFiles/DeepSeek7B/dockerfile
   
5. Starte den Docker container
   
   sudo docker run -it deepseek7b:latest
