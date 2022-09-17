FROM node


# amplify CLI
RUN npm install -g @aws-amplify/cli

# java for Amplify Mock
RUN apt update; apt install -y wget software-properties-common apt-transport-https
RUN wget -qO - https://adoptopenjdk.jfrog.io/adoptopenjdk/api/gpg/key/public | apt-key add -
RUN add-apt-repository --yes https://adoptopenjdk.jfrog.io/adoptopenjdk/deb/
RUN apt update; apt install -y adoptopenjdk-11-openj9

# node version down
RUN npm install -g n
RUN apt update; n 16.17.0