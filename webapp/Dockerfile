

# https://github.com/elastic/elasticsearch-docker
FROM servercentral/praeco

RUN apt-get update -y
RUN apt-get install nano -y
RUN unlink /etc/localtime 
RUN ln -s /usr/share/zoneinfo/America/Santiago /etc/localtime
#RUN PRAECO_ELASTICSEARCH=${PRAECO_ELASTICSEARCH}

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu