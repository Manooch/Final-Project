How to run bcanalysis.py using Docker

Copy these files to your local repository: bcanalysis.py Dockerfile

Run the script in this format: docker build -t <image_name> docker run -it -v /${PWD}:/${PWD} -w /${PWD} <image_name>

Figures are saved in Figures folder