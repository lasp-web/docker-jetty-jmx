# docker-jetty-jmx
Docker Jetty with JMX extension

Sample Run:

docker run -d \
   -p 30000:8080 \
   -v ~/Dev/gitwork/zipservice/dist:/var/lib/jetty/webapps \
   -v ~/Dev/gitwork/zipservice/data:/public/data \
   sroughto/docker-jetty-jmx
