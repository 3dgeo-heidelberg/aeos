# AEOS
[<img src="h++_icon.png">](https://github.com/3dgeo-heidelberg/helios)
AEOS is a QGIS Plugin that integrates some of the functionality of the LiDAR simulator [HELIOS++](https://github.com/3dgeo-heidelberg/helios) into QGIS.

**Install instructions:**

Since the plugin is based on HELIOS++, which is available on conda-forge, QGIS must be installed via conda/mamba. We recommend downloading the [Miniforge distribution](https://github.com/conda-forge/miniforge) and using the package manager `mamba`.

1. Create a new environment with QGIS and HELIOS++:

```
mamba create -n qgis-helios -c conda-forge python=3.12 qgis helios
mamba activate qgis-helios
```

In this environment, you can start the QGIS GUI with the command: `qgis`

2. Install the plugin: 

*Option 1* - Clone the repository into your plugins folder.

*Option 2* - Download the repository as a zip file and unpack it into your plugins folder.

**Hint:** By default your plugins folder is within your QGIS installation here: `QGIS3/profiles/default/python/plugins`. 

## :movie_camera: Tutorial video (German) 

A tutorial video is available for the first version of the plugin:

- Demo-Session: Simulation von Laserscanning mit AEOS, dem QGIS Plugin für HELIOS++ at the FOSSGIS conference 2022:
https://pretalx.com/fossgis2022/talk/JPEZDH/

[![2022 - Simulation von Laserscanning mit AEOS, dem QGIS Plugin für HELIOS++](https://res.cloudinary.com/marcomontalbano/image/upload/v1647686996/video_to_markdown/images/youtube--hO2aqacAWVM-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=hO2aqacAWVM "2022 - Simulation von Laserscanning mit AEOS, dem QGIS Plugin für HELIOS++")
