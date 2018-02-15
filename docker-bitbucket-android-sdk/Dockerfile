FROM jimador/docker-jdk-8-maven-node

RUN wget https://dl.google.com/android/repository/sdk-tools-linux-3859397.zip
RUN unzip sdk-tools-linux-3859397.zip
RUN mkdir android-sdk-linux
RUN cp -r tools android-sdk-linux/
RUN yes | android-sdk-linux/tools/bin/sdkmanager --licenses
