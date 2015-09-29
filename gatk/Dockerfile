FROM ubuntu:14.04

# Update system 
RUN apt-get update

# Run to install java jre
RUN apt-get -y install default-jre

#Run to install java jdk
RUN apt-get -y install default-jdk

# Run to have root as file location or change to have it to another directory (example: "WORKDIR /home")
WORKDIR /root

# Run to copy files from current location to root or change it to another directory (example: "WORKDIR /home")
COPY . /root

# Run to make gatk as alias for jar file ( to run jar file using "gatk -h") or change name to another alias than "gatk" 
RUN echo 'alias gatk="java -jar /root/GenomeAnalysisTK.jar"' >> .bashrc

