# Desplegar docker images
sudo docker build -t dcruz06/appnotas:v4 .

# Ejecutar  
sudo docker run -d -p 5000:5000 dcruz06/appnotas:v4

# Subir docker hub
sudo docker push  dcruz06/appnotas:v4