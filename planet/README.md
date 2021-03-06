[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3484160.svg)](https://doi.org/10.5281/zenodo.3484160)

# Planet Notebook for Neon Science Summit 2019

You can run this notebook in a pre-built Jupyter container using either Binder or CoLab. 

Launch [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/samapriya/neon-science-summit-2019/master)

Launch Google [CoLAB](https://colab.research.google.com/drive/1TKOwiuyvSYWsbzE7rq51DA96rVoVBQZ7)

Citation
```
Samapriya Roy. (2019, October 14). samapriya/neon-science-summit-2019: neon-science-summit-2019 (Version 0.1). Zenodo.
http://doi.org/10.5281/zenodo.3484160
```

## Run Jupyter Lab with Docker

```
docker run -it --rm -v /$HOME:/app --workdir /app -p 8888:8888 -e REDIRECT_URL=http://localhost:8888 cyversevice/jupyterlab-scipy:planet-latest
```

Note you may need to mount the location of your NEON Data when you start the container

```
-v ~/NEON_Downloads:/NEON_Downloads
```

Pull the repo from here or Sam's Github pages

```
git clone https://github.com/samapriya/neon-science-summit-2019
```


# Run Jupyter Lab in CyVerse 

Launch <a href="https://de.cyverse.org/de/?type=quick-launch&quick-launch-id=3915f0c6-d817-40b3-8475-2a7b93d928a8&app-id=1d35dc48-eb93-11e9-b6b7-008cfa5ae621" target="_blank"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a>

## Requirements:

(1) Register for CyVerse https://user.cyverse.org/

(2) Log into the Discovery Environment: https://de.cyverse.org

<p align="center"><img src='https://github.com/cyverse-gis/neon-science-summit-2019/blob/master/gif/DE_launch.gif?raw=true' width='750'></p>

