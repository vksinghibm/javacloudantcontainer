FROM registry.ng.bluemix.net/ibmliberty:latest
COPY JavaCloudantApp.war /config/apps/
COPY server.xml /config/
EXPOSE 9080
CMD ["/opt/ibm/wlp/bin/server", "run", "defaultServer"]
