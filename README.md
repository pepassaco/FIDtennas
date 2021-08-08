# FIDtennas
Open-source RF hardware repository. Visit [FIDtennas](https://www.fidtennas.ga) for additional info about this project.

*Designs by Pablo EA1FID*

## Structure of the repo

This repo follows the next structure:

    .FIDtennas
    ├── README.md
    |
    ├── 3D parts
    |
    ├── Antennae
    │   ├── Satellite
    │   │   ├── Aiga
    │   │   │   ├── images
    │   │   │   ├── results
    │   │   │   ├── model
    │   │   │   └── README.md
    │   │   ├── ...
    │   |
    │   ├── 6m
    │   │   └── ...
    │   |
    │   ├── 4m
    │   │   └── ...  
    |   ├── ...
    |
    └── Other   

Inside the *images* forder there will be images either of the 3D model of the antenna, its plans or the final build. 

The folder *results* contains the .s1p or .csv files corresponding to real-life antenna measurements.

Inside *model* there is the .cst files of the antenna model used during the design phase in CST Studio.

Finally, the README file of every antenna describes its main characteristicas and specifications and provides the necessary plans or building guides if needed.

## License

Al this designs are under a GNU GPL v3 license. You may freely use them to build your own hardware, modify it according to your needs or improve it, always mentioning either FIDtennas or EA1FID as the designer of the original version.
