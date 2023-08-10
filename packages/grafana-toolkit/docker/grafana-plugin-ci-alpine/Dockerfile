FROM alpine:3.18.3 
USER root 
ADD scripts scripts
ADD install /usr/local/bin
WORKDIR scripts
RUN ./deploy.sh
