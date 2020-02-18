# sclite
Here I am providing example tsv file and how output files from Sclite actually look like

# Which docker image to download?
https://hub.docker.com/r/antsu/sclite

Use my tsv files to generate you report

# After pulling the images your commmand for running images will be:
docker run -it -v ../SCLITE Docker/tsv_in/:/tsv_in -v ../SCLITE Docker/tsv_out/:/tsv_out antsu/sclite:latest
