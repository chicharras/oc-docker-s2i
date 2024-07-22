# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# Cambiando parametros del Dockerfile para generar neva salida en OCP pod.
#CMZ
#CMD ["/bin/bash", "-c", "sleep infinity"]
 CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
