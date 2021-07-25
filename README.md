# FIDtennas
Open-source RF hardware repository. Visit [FIDtennas](https://www.fidtennas.ga) for additional info about this project.

*Designs by Pablo EA1FID*

## Structure of the repo

This repo follows the next structure:

    .FIDtennas
    ├── README.md
    |
    ├── Satellite
    │   ├── *Aiga*
    │   │   ├── images
    │   │   ├── results
    │   │   │   ├── graphics
    │   │   │   └── data
    │   │   ├── model
    │   │   │   ├── 3D
    │   │   │   └── CST
    │   │   └── README.md
    │   ├── ...
    |
    ├── 6m
    │   └── ...
    |
    ├── 4m
    │   └── ...  
    ... 

Inside the *images* forder there will be images either of the 3D model of the antenna or of the final build. 

The folder *results* contains two subfolders. *graphics* has representarions of the main parameters of the antenna (S11, SWR, radiation patterns...), while *data* contains the .s1p or .csv files from which the aforementioned graphs were obtained.

Inside *model* there are also two folders. *3D* just has the necessary .stl files for printed the required 3D parts (if any), while *CST* contains the .cst files of the antenna model used during the design phase in CST Studio.

Finally, the README file of every antenna describes its main characteristicas and specifications and provides the necessary plans or building guides if needed.

## License

Al this designs are under a GNU GPL v3 license. You may freely use them to build your own hardware, modify it according to your needs or improve it, always mentioning either FIDtennas or EA1FID as the designer of the original version.
