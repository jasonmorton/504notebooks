To simplify installation, you might want to use Docker.  Here is the command I use to start the Jupyter server.

```bash
docker run -d -p 8888:8888  -v /home/jason/Dropbox/504notebooks:/home/jovyan/work jupyter/datascience-notebook 
```
The -v flag mounts the local directory /home/jason/Dropbox/504notebooks to the working director /home/jovyan/work inside the container.  For you the first directory will be wherever you checked out the 504notebooks repository.
