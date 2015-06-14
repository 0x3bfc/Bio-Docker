#IGV-Tools

Build igv-tools Image

	$ tar xvjf IGVTools.tar.bz2
	$ sudo docker build -t igvtools .

Run the following command line to test bowtie

	$ sudo docker run --rm igvtools igvtools

