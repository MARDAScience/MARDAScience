# Marda Science

We are a tiny science consultancy. We consist of Dr Daniel Buscombe and Dr Maria Campbell. Our [website](https://www.mardascience.com) is still under development but details some of the work that we do. This is the landing page for Dan's page of software repositories and datasets that concern projects in Machine Learning, Deep Learning, Remote Sensing, Computer Vision, Image Processing, and Geospatial analysis. It gives a more complete picture. Dan often [tweets](https://twitter.com/magic_walnut) about the status of various projects and how to use his software tools. Some teaching resources are hosted through our [Gitlab repository](https://gitlab.com/mardascience).

Dan's other github handle is [dbuscombe-usgs](https://github.com/dbuscombe-usgs). He develop codes collaboratively and host them mostly in a range of Github organizations, listed below:

* [Doodleverse](https://github.com/Doodleverse)
* [DigitalGrainSize](https://github.com/DigitalGrainSize)
* [SatelliteShorelines](https://github.com/SatelliteShorelines)
* [BenthicSubstrateMapping](https://github.com/BenthicSubstrateMapping)
* [CoastTrain](https://github.com/CoastTrain)
* [LearnImageSegmentationWithUnets](https://github.com/LearnImageSegmentationWithUnets)
* [MLMondays](https://github.com/MLMondays)
* [OpticalWaveGauging](https://github.com/OpticalWaveGauging)
* [FloodCamML](https://github.com/FloodCamML)
* [CoastalBuildings](https://github.com/CoastalBuildings)
* [C-GRASP](https://github.com/C-GRASP)


## Contents
- [Media](#media)
- [Active Software Projects](#active-software-projects)
    - [Doodleverse](#doodleverse)
    - [SediNet](#sedinet)
    - [OWG](#owg)
    - [Ping-mapper](#ping-mapper)
    - [RetinaDamage](#retinadamage)
    - [GobyNet](#gobynet)
    - [RegionalGrainSizeModel](#regionalgrainsizemodel)
    - [prism](#prism)
    - [PBR filter](#pbr)
    - [pysesa](#pysesa)
- [Teaching materials](#teaching-materials)
    - [ML-Mondays](#ML-Mondays)
    - [Image Segmentation with UNets](#Image-Segmentation-with-UNets)
- [Datasets](#datasets)
    - [Doodleverse Zenodo releases](#Doodleverse-Zenodo-releases)
    - [Other Zenodo releases](#Other-Zenodo-releases)
    - [Coast Train](#Coast-Train)
    - [USGS ScienceBase data releases](#USGS-ScienceBase-data-releases)
    - [Other data releases](#Other-data-releases)
- [Demo Apps](#Demo-Apps)
    - [Hugging Face](#Hugging-Face)
    - [Streamlit](#Streamlit)


## Media

> November 2022: CSDMS webinar. 

Part 1 of the 2-part, ``Intro to the Doodleverse'' webinar for the Community Surface Dynamics Modeling System fall webinar series [youtube link](https://youtu.be/BarGUQ5CuA0) concentrates on [Doodler]()

Part 2 of the 2-part, ``Intro to the Doodleverse'' webinar for the Community Surface Dynamics Modeling System fall webinar series [youtube link](https://www.youtube.com/watch?v=mSsUT88IIH8) concentrates on [Segmentation Gym]()

> November 2022: satellite-image-deep-learning Podcast

Interview with [Robin Cole](https://twitter.com/robmarkcole) for the [satellite-image-deep-learning](https://www.satellite-image-deep-learning.com/) podcast and newsletter entitled, ``Into the Doodleverse'' 
* [substack link](https://robmarkcole.substack.com/p/satellite-image-segmentation-with)
* [youtube link](https://www.youtube.com/watch?v=0I1TOOGfdZ0)

> August 2022: Bodega Bay talk on applications of Deep Learning for coastal monitoring

Talk entitled "Developing Deep Learning Design Patterns for Large-Scale Coastal Monitoring", for the John & Mary Louise Riley Bodega Marine Laboratory Seminar Series, UC Davis Bodega Marine Lab, Bodega Bay, CA.
* [youtube link](https://www.youtube.com/watch?v=SnmotT2hDn0)

> December 2021: The International Society for Photogrammetry and Remote Sensing Student Consortium (ISPRS SC)

Interview (5 pages) in SpeCtrum (Vol. 15, No. 2), the official newsletter of the The International Society for Photogrammetry and Remote Sensing Student Consortium (ISPRS SC)
* [link to pdf](http://sc.isprs.org/files/sc/newsletter/ISPRS-SC-Spectrum-Vol15-No2.pdf)


> March 2016: USGS "What's the Big Idea?""

My acoustic remote sensing research was featured in the video on the YouTube channel of the U.S. Geological Survey
* [Whats the Big Idea? Using Sound to Remotely Sense the Riverbed](https://www.youtube.com/watch?v=zNqpuKf2O7o)

> July 2015: American Geophysical Union Research Spotlight

My acoustic remote sensing research featured in EOS Earth and Space Science News
* [Using Sound Waves to Study Grand Canyon Sediment](https://eos.org/research-spotlights/using-sound-waves-to-study-grand-canyon-sediment)


> September 2012]{JGR-Oceans Editor's Highlight

My oceanographic research was featured in an article published in the Journal of Geophysical Research - Oceans.
*[Novel observations of currents and drag generated by a tsunami](http://agupubs.onlinelibrary.wiley.com/agu/article/10.1029/2012JC007954/editor-highlight/}


## Active Software Projects

### Doodleverse

> Deep-learning based semantic segmentation of geospatial data. 

In the past two years I led the development and now maintain a set of TensorFlow-based tools specifically designed for this task - from developing training data to creating deployment ready models. The set of tools is available on [Github Doodleverse Org.](https://github.com/Doodleverse). I have recently [talked](https://www.youtube.com/watch?v=0I1TOOGfdZ0)about these tools and how they are being [applied](https://www.youtube.com/watch?v=SnmotT2hDn0) in production. 

That work has spawned the development of several downstream applications for specific tasks. For example, CoastSeg and Seg2Map described below

### CoastSeg

> An interactive interface to download satellite imagery using CoastSat from Google Earth Engine, extracting shorelines from satellite imagery, and applying segmentation models to satellite imagery
> A mapping extension for CoastSat using Segmentation Zoo models

In the past year I have overseen a small team developing satellite-image based shoreline [mapping tools](https://github.com/SatelliteShorelines/CoastSeg) as we work towards a prospectus outlined in a [recent paper](https://doi.org/10.31223/X54P9Z). 


### Seg2Map
> An interactive web map app for geospatial label imagery generated within the Doodleverse

Another generic toolbox for semantic segmentation of geospatial imagery is [Seg2Map](https://github.com/Doodleverse/seg2map). Display the imagery on a web map, and apply segmentation models to create labels and maps

### SediNet

> Deep-learning based estimation of sediment grain size

Several of my model frameworks, including [SediNet](https://github.com/DigitalGrainSize/SediNet), combine to amass a citizen science database of beach sand measurements for the U.S. Army Corps of Engineers, called the [SandSnap project](https://sandsnap-erdcchl.hub.arcgis.com/). SediNet is software for application of deep convolutional neural networks to estimation of quantitative and qualitative properties of sediment in photographic imagery. 

Other (older) software for automated analyses of grain size from images of sediment usign wavelets is also [available](https://github.com/dbuscombe-usgs/pyDGS) and widely used, having amassed several hundred academic paper [citations](https://scholar.google.com/citations?user=bwVl0NwAAAAJ&hl=en).

### OWG

>Deep-learning based estimation of nearshore ocean wave properties

I research methods to measure surf zone waves from satellite imagery by adapting a [deep learning model framework](https://github.com/OpticalWaveGauging/OpticalWaveGauging_DNN) I developed to larger scales.

Software for application of deep convolutional neural networks to estimation of ocean wave properties from time-series of imagery are available in the [Github Optical Wave Gauging Org.](https://github.com/OpticalWaveGauging)

### Ping-mapper

> Sidescan sonar processing and analysis

I have been involved in sidescan sonar processing for a decade. I oversee a software project for reading, processing and analysis of Humminbird sidescan data, called [Ping-mapper]https://github.com/CameronBodine/PINGMapper/). It is based on older software I wrote for for reading, processing and analysis of Humminbird sidescan data. Source code available in Python/Cython [here](https://github.com/dbuscombe-usgs/PyHum) is now archived, having been succeeded by PING-Mapper.

### RetinaDamage

> Deep Learning for estimating damage to buildings due to natural disasters

This project trained a [RetinaNet model](https://github.com/CoastalBuildings/HurricaneHarvey_buildingdamage) to detect building damage in Maxar satellite imagery.

### GobyNet

> Deep-learning based detection of benthic fish

I have written software for automated detection of camouflaged benthic fish using models based on RetinaNet and deep residual U-Net. Source code currently available in Python (link soon).

### RegionalGrainSizeModel

> Machine Learning for estimating beach grain size over regional scales

This ongoing project uses [boosted regression trees](https://github.com/C-GRASP/RegionalGrainSizeModel) to estimate sand beach grain size over regional scales from a suite of covariates like beach slope, tide, and wave climate.

### prism

> Multibeam processing and analysis

Software for probabilistic seafloor habitat mapping using multibeam backscatter. Code [here](https://github.com/dbuscombe-usgs/prism)

### PBR-filter
Novel {P}ansharpening by {B}ackground {R}emoval algorithm for sharpening RGB images. Code [here](https://github.com/dbuscombe-usgs/PBR_filter)

### pysesa

Software for spatially explicit analyis of point clouds and spatially distributed data. Code (now archived) is [here](https://github.com/dbuscombe-usgs/pysesa).


## Teaching materials

I have taught several classes on Machine Learning and data science principles, including development and teaching of Machine Learning courses for my coworkers and the wider geoscience community. 

### ML-Mondays
Teaching materials and software for application of deep convolutional neural networks for analysis of photographic imagery. Supervised and semi-supervised deep learning models and data for image segmentation, and object detection. Source code currently available in Python on the [ML-Mondays Github Org.](https://github.com/dbuscombe-usgs/MLMONDAYS)

### Image Segmentation with UNets

* Check out my ["LearnImageSegmentationWithUnets" Github Org.](https://github.com/LearnImageSegmentationWithUnets)! This links with two online courses hosted using GitLab
    * [Binary image_segmentation for geosciences](https://mardascience.gitlab.io/binary_image_segmentation_for_geosciences/#/), hosted from this [gitlab repo](https://gitlab.com/mardascience/binary_image_segmentation_for_geosciences)
    * [Deep learning for landscape classification](https://mardascience.gitlab.io/deep_learning_landscape_classification/#/), hosted from this [gitlab repo](https://gitlab.com/mardascience/deep_learning_landscape_classification)

* I wrote an online course for [Manning Publications](https://www.manning.com/liveproject/monitoring-changes-in-surface-water-using-satellite-image-data) for detection of lakes from Sentinel-2 imagery using deep learning.



## Datasets

### Doodleverse Zenodo releases

#### ML models

##### Current CoastSeg models

###### 2-class (water/other)
* Buscombe, Daniel. (2023). Doodleverse/Segmentation Zoo Res-UNet models for 2-class (water, other) segmentation of Sentinel-2 and Landsat-7/8 1-band MNDWI images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7557080)

* Buscombe, Daniel. (2023). Doodleverse/Segmentation Zoo Res-UNet models for 2-class (water, other) segmentation of Sentinel-2 and Landsat-7/8 1-band NDWI images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7557072)

* Buscombe, Daniel. (2022). Doodleverse/Segmentation Zoo Res-UNet models for 2-class (water, other) segmentation of Sentinel-2 and Landsat-7/8 3-band (RGB) images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7448405)

* Buscombe, Daniel. (2022). Doodleverse/Segmentation Zoo Res-UNet models for 2-class (water, other) segmentation of Sentinel-2 and Landsat-7/8 5-band (RGB+NIR+SWIR) images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7448390)


###### 4-class (water/whitewater/sediment/other)
* Buscombe, D. (2022). Doodleverse/Segmentation Zoo Res-UNet models for 4-class (water, whitewater, sediment and other) segmentation of Sentinel-2 and Landsat-7/8 7-band (RGB+NIR+SWIR+NDWI+MNDWI) images of coasts. [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7358284)

* Buscombe, D. (2022). Doodleverse/Segmentation Zoo Res-UNet models for 4-class (water, whitewater, sediment and other) segmentation of Sentinel-2 and Landsat-7/8 1-band MNDWI images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7352850)

* Buscombe, D. (2022). Doodleverse/Segmentation Zoo Res-UNet models for 4-class (water, whitewater, sediment and other) segmentation of Sentinel-2 and Landsat-7/8 1-band NDWI images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7352859)

* Buscombe, D. (2022). Doodleverse/Segmentation Zoo Res-UNet models for 4-class (water, whitewater, sediment and other) segmentation of Sentinel-2 and Landsat-7/8 5-band (RGB+NIR+SWIR) images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7344606)

* Buscombe, D. (2022). Doodleverse/Segmentation Zoo Res-UNet models for 4-class (water, whitewater, sediment and other) segmentation of Sentinel-2 and Landsat-7/8 3-band (RGB) images of coasts. (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6950472)

##### Older CoastSeg models

* Buscombe, D. (2022) Segmentation Zoo UNet models for Landsat-8 satellite imagery, Coast Train v1 Landsat-8 4-class subset. (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6230083)

* Buscombe, D. (2022) Segmentation Zoo Res-UNet models for Landsat-8 satellite imagery, Coast Train v1 Landsat-8 4-class subset. (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6229071)

##### SandSnap models
* Buscombe, D. (2022) Doodleverse/Segmentation Zoo Res-UNet models for identifying coins in photos of sediment. (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6229579)

##### Watermasking models
* Buscombe, D. (2022) Doodleverse/Segmentation Zoo UNet models for identifying water in oblique aerial photos of coasts. (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6235090)

* Buscombe, D. (2022) Doodleverse/Segmentation Zoo Res-UNet models for identifying water in oblique aerial photos of coasts. (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6234122)


#### Labeled imagery for segmentation models
* Buscombe, D. (2022). Images and 2-class labels for semantic segmentation of Sentinel-2 and Landsat RGB, NIR, and SWIR satellite images of coasts (water, other) (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7384263)

* Buscombe, D. (2022). Images and 2-class labels for semantic segmentation of Sentinel-2 and Landsat RGB satellite images of coasts (water, other) (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7384242)

* Buscombe, D. (2022). Images and 4-class labels for semantic segmentation of Sentinel-2 and Landsat RGB, NIR, and SWIR satellite images of coasts (water, whitewater, sediment, other) (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7344571)

* Buscombe, D, Goldstein, E, Bernier, J., Bosse, S., Colacicco, R., Corak, N., Fitzpatrick, S., del Jesús González Guillén, A., Ku, V., Paprocki, J., Platt, L., Steele, B., Wright, K., & Yasin, B. (2022). Images and 4-class labels for semantic segmentation of Sentinel-2 and Landsat RGB satellite images of coasts (water, whitewater, sediment, other) (v1.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7335647)

* Buscombe, D. (2022). Cape Hatteras Landsat8 RGB Images and Labels for Image Segmentation using the program, Segmentation Zoo (v3.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7232051)

* Buscombe, D., et al. (2022) Labeled Images of Sand and Coins v2 (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6232246)

* Goldstein, E. B., et al. (2022) Segmentation Labels for Emergency Response Imagery from Hurricane Barry, Delta, Dorian, Florence, Isaias, Laura, Michael, Sally, Zeta, and Tropical Storm Gordon (Version v1) [Data set]. Zenodo.
[link](https://doi.org/10.5281/zenodo.7268083)


### Other Zenodo dataset releases

* McFall, M., et al. (2022) The SandSnap Project: 2020 -- 2021 sieved grain-size data and associated sediment imagery (0.0.1) [Data set]. Zenodo.
[link](https://doi.org/10.5281/zenodo.7063226)

* Goldstein, E. B., et al. (2022) Labels for Emergency Response Imagery from Hurricane Barry, Delta, Dorian, Florence, Ida, Isaias, Laura, Michael, Sally, Zeta, and Tropical Storm Gordon (2.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7217621)

* Buscombe, D., et al. (2022) Monthly CDIP:MOP-alongshore modeled wave statistics for California, January 2000 - July 2022 (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6946132)

* Buscombe, D., et al. (2022) Yearly CDIP:MOP-alongshore modeled wave statistics for California, January 2000 - July 2022 (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6946105)

* Buscombe, D., et al. (2022) Shoreline data at 30-m spatial resolution for 2001 coastal provinces or regions of the world, in geoJSON format. (v1.0.0) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.6917963)

* Buscombe, D., et al. (2022) Shoreline data at 30-m spatial resolution for 298 coastal counties of the conterminous USA, in geoJSON format. (v0.0.1) [Data set]. Zenodo. [link](https://doi.org/10.5281/zenodo.7033367)

* Buscombe, D., et al. (2022) Preliminary Coastal Grain Size Portal (C-GRASP) dataset. Version 1, January 2022, Zenodo [link](https://zenodo.org/record/5874231#.YeeQbVuIbRZ)

* Goldstein et al. (2022) Labels for Hurricane Florence (2018) Emergency Response Imagery from NOAA. 10.6084/m9.figshare.11604192.v1 [link](https://figshare.com/articles/dataset/Labels_for_Hurricane_Florence_2018_Emergency_Response_Imagery_from_NOAA/11604192)

* Goldstein et al. (2022) Labels for Emergency Response Imagery from Hurricane Florence, Hurricane Michael, and Hurricane Isaias (Version 1.0) [link](http://doi.org/10.5281/zenodo.4272064)


### Coast Train

* Wernette, P., et al. (2022) Coast Train--Labeled imagery for training and evaluation of data-driven models for image segmentation: U.S. Geological Survey data release, [link](https://doi.org/10.5066/P91NP87I). Check out the [website](https://coasttrain.github.io/CoastTrain/) for more details.

### USGS ScienceBase data releases

* Ritchie, M., et al. (2022) Aerial photogrammetry data and products of the North Carolina coast: U.S. Geological Survey data release. [link](https://doi.org/10.5066/P9K3TWY7)

* Kaplinski, M., et al. (2022) Channel mapping Glen Canyon Dam to Lees Ferry in Glen Canyon National Recreation Area, Arizona - Data: U.S. Geological Survey data release, [link](https://doi.org/10.5066/P98GFP93)

* Dean, D.J., et al.(2022) Suspended-sediment, bedload, bed-sediment, and multibeam sonar data in the Chippewa River, WI: U.S. Geological Survey data release, [link](https://doi.org/10.5066/P9HT6RLX)

* Ritchie, A.C. et al. (2021) Aerial photogrammetry data and products of the North Carolina coast—2018-10-06 to 2018-10-08, post-Hurricane Florence: U.S Geological Survey data release, [link](https://doi.org/10.5066/P9CA3D8P)

* Kranenburg et al. (2020) Post-Hurricane Florence aerial imagery: Cape Fear to Duck, North Carolina, October 6–8, 2018: U.S. Geological Survey data release. [link](https://coastal.er.usgs.gov/data-release/doi-P91KB9SF/)

* Kasprak et al. (2018) River Valley Sediment Connectivity Data, Colorado River, Grand Canyon, Arizona: U.S. Geological Survey data release. [link](https://doi.org/10.5066/P9SX3MGY/)

### Other data releases
* Buscombe, D., Goldstein, E. G., Sherwood, C. R., Bodine, C., Favela, J., Fitzpatrick, S., et al. (2022). Dataset accompanying Buscombe et al. Human-in-the-loop segmentation of Earth surface imagery. [link](https://doi.org/10.5061/dryad.2fqz612ps)

## Demo Apps

### Hugging Face
* [sat_RGB_2class_7384255](https://huggingface.co/spaces/dbuscombe/sat_RGB_2class_7384255): Segment 3-band (R+G+B) satellite imagery into 2 classes (water, other)
* [sat_RGB_4class_6950472](https://huggingface.co/spaces/dbuscombe/sat_RGB_4class_6950472): Segment 3-band (R+G+B) satellite imagery into 4 classes (water, whitewater, sediment, other)
* [sat_5band_2class_7388008](https://huggingface.co/spaces/dbuscombe/sat_5band_2class_7388008): Segment 5-band (R+G+B+NIR+SWIR) satellite imagery into 2 classes (water, other)
* [sat_5band_4class_7344606](https://huggingface.co/spaces/dbuscombe/sat_5band_4class_7344606): Segment 5-band (R+G+B+NIR+SWIR) satellite imagery into 4 classes (water, whitewater, sediment, other)
* [WaterMasker CA](https://huggingface.co/spaces/dbuscombe/WaterMaskerCA): Segment 3-band (R+G+B) aerial imagery into 2 classes (water, other)
* [Sandy Coins](https://huggingface.co/spaces/dbuscombe/SandyCoins): Segment 3-band (R+G+B) sediment imagery into 2 classes (sediment, coin)
* [Digital Grain Size](https://huggingface.co/spaces/dbuscombe/DigitalGrainSize): estimate grain size distribution of 3-band (R+G+B) sediment imagery
* [Satellite Super Resolution](https://huggingface.co/spaces/dbuscombe/SatelliteSuperResolution): 3x spatial resolution of satellite imagery

### Streamlit
* [Create binary mask](https://dbuscombe-usgs-streamlit-segmentation-app-app-gqqs4o.streamlit.app/): Manually segment 3-band (R+G+B) aerial imagery into 2 classes 
* [Water Masker CA](https://dbuscombe-usgs-watermaskerapp-run-27dt42.streamlit.app/): Segment 3-band (R+G+B) aerial imagery into 2 classes (water, other)
* [Resize Images](https://dbuscombe-usgs-resizeimages-resize-ijue0d.streamlit.app/): resize 3-band (R+G+B) images
* [PBR filter](https://dbuscombe-usgs-pbrapp-pbr-57wxr4.streamlit.app/): apply the [PBR filter](https://github.com/dbuscombe-usgs/PBR_filter) to 3-band (R+G+B) imagery
* [DigitalGrainSize](https://dbuscombe-usgs-dgsapp-run-o114m8.streamlit.app/): estimate grain size distribution of 3-band (R+G+B) sediment imagery