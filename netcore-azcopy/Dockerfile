FROM microsoft/dotnet:1-runtime

MAINTAINER George Guskov

RUN apt-get update -y
RUN apt-get install -y wget

RUN echo "Downloading azcopy..."
RUN wget -O azcopy.tar.gz https://aka.ms/downloadazcopyprlinux
RUN echo "Unpacking azcopy..."
RUN tar -xf azcopy.tar.gz
RUN echo "Installing azcopy..."
RUN ./install.sh