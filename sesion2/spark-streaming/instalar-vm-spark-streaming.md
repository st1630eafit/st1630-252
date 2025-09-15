# crear una VM Linux AMI 2023

    sudo dnf update -y

# instalar spark local:
# https://spark.apache.org/
# https://spark.apache.org/downloads.html
## revisar y probar la última versión de apache spark 
### Spark 4.0.1 (Sep 06 2025)
### Spark 3.5.6 (May 29 2025)
# instalarlo en: (si es aws con ubuntu 22.04)
## "SPARK_HOME" = "/home/ec2-user/spark-4.0.1-bin-hadoop3"


    sudo dnf install java (instala la versión 24)
    sudo dnf install java-11-amazon-corretto-devel

    export JAVA_HOME=/usr/lib/jvm/java-11-amazon-corretto.x86_64/

    sudo dnf install python3.12
    sudo dnf install python3-pip

instalar netcat en linux:

    sudo dnf install nc

# abrir 2 o 3 terminarles, 
# termina1 1:

    nc -lk 9999

# terminal 2:

    python3 sparkStreaming-ejemplo1.python3

# escribe varias oraciones en texto libre en la terminal 1

# puedes utilizar una terminal 3 para revisar los archivos de salida para el ejemplo: sparkStreaming-ejemplo2.py






