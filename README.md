This is a collection of R notebooks to supplement a class on the analysis of discrete data.  The github viewer is unreliable; you can see the notebooks at https://nbviewer.jupyter.org/github/jasonmorton/504notebooks/blob/master/Binomial_CI_Wald.ipynb etc.

You can view the notebooks just by navigating to them.  If you'd like to run and  modify them, you'll need to install Jupyter with an R kernel on your local machine.  To simplify installation, you might want to use Docker.  Once you install Docker, and checkout this repository, you can start the Jupyter server with the following command.

```bash
docker run -d -p 8888:8888  -v /home/jason/Dropbox/504notebooks:/home/jovyan/work jupyter/datascience-notebook 
```
Then open localhost:8888 in your browser.

The -v flag mounts the local directory (for me it is /home/jason/Dropbox/504notebooks) to the working directory /home/jovyan/work inside the docker container.  For you the first directory will be wherever you checked out this 504notebooks repository.

Note that the code in these notebooks is intended to explain the concepts. There is usually a faster, built-in, or more elegant way to accomplish the same ends.

The [course notes are freely available](https://onlinecourses.science.psu.edu/stat504/) and generally correspond closely to these notebooks.
