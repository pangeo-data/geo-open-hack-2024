# Scaling on HPC/HTC

In this section, we will show how to move from the cloud to HPC/HTC to scale. 

For this section, you need to have an account on [Spider](https://doc.spider.surfsara.nl/en/latest/Pages/about.html) from [SURF](https://www.surf.nl/). 
We are using [Apptainer](https://apptainer.org) and for the training, we will be using an image with less Python packages (sufficient for executing all the notebooks from the tutorial). 

## Launch JupyterLab and use dask on Spider

### Set up

First, login to spider:

```
ssh -Y2C -i $HOME/.ssh/id_rsa $USER@spider.surfsara.nl
```

We prepared the dask configuration file for spider that you need to copy:

```
cd $HOME
mkdir -p ~/.config/dask
cp /project/geocourse/Software/pangeo/JupyterDaskOnSLURM/config/dask/config_spider.yml ~/.config/dask/config.yml
```

Then copy the batch job we prepared to submit on spider and start jupyterLab:

```
cp /project/geocourse/Software/pangeo/JupyterDaskOnSLURM/scripts/jupyter_dask_spider_container.bsh $HOME/scripts/.
```

### Submit job to start jupyterLab

Whenever you want to start a JupyterLab, you would need to submit `jupyter_dask_spider_container.bsh`:

```
sbatch jupyter_dask_spider_container.bsh
```

### Open jupyterLab from your local computer

Open another terminal on your computer and from your local terminal. The job you submitted should be running. You can check it using the following command:

```
squeue -u $USER
```

Then check the slurm output, where you should have something like:

```
ssh -i /path/to/private/ssh/key -N -L 8889:wn-ca-03:9300 geocourse-teacher09@spider.surf.nl
```

Copy/paste the command given in your slurm output but update the path to the ssh key you are using to login to spider (e.g. `/home/annef/.ssh/id_rsa`).

- If you copy the command above, make sure to change the username `geocourse-teacher09` to your username on spider.

 
## Create your own image

TODO
Follow these steps if you want to know more and create your own image. 
