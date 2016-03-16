FROM tutum/tomcat:8.0
MAINTAINER John Starich <johnstarich@johnstarich.com>

# Use Tutum's pre-installed Launchpad PPA for Java installation
RUN apt-get update && \
    apt-get install -y oracle-java8-set-default && \
    rm -rf /var/lib/apt/lists/* && \
    rm -rf /var/cache/oracle-jdk8-installer

