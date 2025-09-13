# st1630-252

## instrucciones para instalar docker en ubuntu 22.04 en AWS

    sudo apt update
    sudo apt install docker.io -y
    sudo apt install docker-compose -y
    sudo systemctl enable docker
    sudo systemctl start docker
    sudo usermod -a -G docker ubuntu 