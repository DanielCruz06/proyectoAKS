# Desplegar docker images
sudo docker build -t kubermatic-dl:v1 .

# Ejecutar  
sudo docker run -d -p 5000:5000 kubermatic-dl:v1

# Subir docker hub
sudo docker tag 3d7c6cc40f10 dcruz06/kubermatic-dl

sudo docker push  dcruz06/kubermatic-dl