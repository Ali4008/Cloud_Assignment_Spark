Run the following command in cmd:
## docker run -it --name spark-container -p 8888:8888 -v E:\Netflix_data:/workspace jupyter/all-spark-notebook
This Docker command runs a container named spark-container using the jupyter/all-spark-notebook image. It maps the host's E:\Netflix_data folder to the container's /workspace directory for data sharing and forwards port 8888 on the host to port 8888 in the container, enabling access to Jupyter Notebook. The -it flag makes the container interactive, allowing user input.
