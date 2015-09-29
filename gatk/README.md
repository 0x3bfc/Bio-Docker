GATK
Downloading and installing 

Requirments : 
	1- System updateJava Runetime Enviroment (jre)
	2- updateJava Runetime Enviroment (jre)
	3- GATK package 

Method #1 (Manual):
	1. System update :
		 Run "sudo apt-get update" (ubnutu)

	2. Installing Java Runetime Enviroment (jre) :
		 Run "apt-get install default-jre" (ubnutu)

	3. GATK package :
		1- Go to website "https://www.broadinstitute.org/gatk/download/"
		2- Download file (Example GenomeAnalysisTK-3.3-0)
		3- Unpack file (Example by Running "tar xjf GenomeAnalysisTK-3.3-0.tar.bz2")

	4. Testing GATK :
		 Run "java -jar GenomeAnalysisTK.jar -h"
		 OR 
		 alias gatk="java -jar /root/GenomeAnalysisTK.jar"
		 Run "gatk -h"

Method #2 (Dockerfile) :

	1. GATK package :
		1- Go to website "https://www.broadinstitute.org/gatk/download/"
		2- Download file (Example GenomeAnalysisTK-3.3-0)
		3- Unpack file (Example by Running "tar xjf GenomeAnalysisTK-3.3-0.tar.bz2")
	
	2. Run Dockerfile (In same directory as unpacked GATK)
	
	3.  Testing GATK :
		 Run "java -jar GenomeAnalysisTK.jar -h" || gatk -h
		
