# Docker image for http://www.alfresco.com/
FROM debian
MAINTAINER jonathan lung <vapr@sojournlabs.com>
RUN apt-get update
RUN apt-get install -y \
    wget
ADD install_alfresco /bin/install_alfresco
ADD alfresco-options /bin/alfresco-options
