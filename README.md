# Waste datasets review

List of datasets with any kind of litter, garbage, waste and trash. Created during the [detectwaste.ml](https://detectwaste.ml/) project

Today, more than 300 million tons of plastic are produced annually. Plastic is everywhere and we constantly use it in our daily life.

The idea of **detect waste project** is to use Artificial Intelligence to detect plastic waste in the environment. Our solution will be applicable for video and photography. Our goal is to use AI for Good.

## Contributing

Feel free to add **issue** with short description of new dataset or create a **pull request** - add the new dataset to the table or fill missing description.

# Summary

| Name                               	| No. categories 	| No. subcategories              	| No. images 	| Annotation                	| Comment                              	| Website                                                             	| Description        	|
|------------------------------------	|----------------	|--------------------------------	|------------	|---------------------------	|--------------------------------------	|---------------------------------------------------------------------	|--------------------	|
| TrashCan 1.0                       	| 3              	| 34                             	| 7 212      	| Instance-Segmentation     	| Underwater images                    	| [website](https://conservancy.umn.edu/handle/11299/214865)                     	| :heavy_check_mark: 	|
| Trash-ICRA19                       	| 3              	| 34                             	| 5 700      	| Detection                 	| Underwater images                    	| [website](https://conservancy.umn.edu/handle/11299/214366)                     	| :heavy_check_mark: 	|
| TACO                               	| 28             	| 60                             	| 1 500      	| Segmentation              	| Waste in the wild                    	| [website](http://tacodataset.org/stats)                                        	| :heavy_check_mark: 	|
| TACO bboxes                        	| 7              	| 60                             	| WIP        	| Detection                 	| Waste in the wild                    	| WIP                                                                 	| :heavy_check_mark: 	|
| UAVVaste                           	| 1              	| -                              	| 772        	| Segmentation              	| Drone dataset                        	| [github](https://github.com/UAVVaste/UAVVaste)                                	| :heavy_check_mark: 	|
| Trashnet                           	| 6              	| -                              	| 2 527      	| Classification            	| Clear background                     	| [github](https://github.com/garythung/trashnet)                               	| :heavy_check_mark: 	|
| WaDaBa                             	| 8              	| color,size, shape, or material 	| 4 000      	| Classification            	| Plastic dataset, clear background    	| [website](http://wadaba.pcz.pl/)                                               	| :heavy_check_mark: 	|
| GLASSENSE-VISION                   	| 7              	| 136                            	| 2 000      	| Classification            	| Home-supplies, clear background      	| [website](http://www.slipguru.unige.it/Data/glassense_vision/)                 	| :heavy_check_mark: 	|
| Waste Classification data          	| 2              	| -                              	| ~25 000    	| Classification            	| Scraped from google search           	| [kaggle](https://www.kaggle.com/techsash/waste-classification-data)           	| :heavy_check_mark: 	|
| Waste Classification Data v2       	| 3              	| -                              	| ~27 500    	| Classification            	| Scraped from google search           	| [kaggle](https://www.kaggle.com/sapal6/waste-classification-data-v2)          	| :heavy_check_mark: 	|
| Waste Images from Sushi Restaurant 	| 16             	| -                              	| 500        	| Classification            	| Clear background                     	| [kaggle](https://www.kaggle.com/arthurcen/waste-images-from-sushi-restaurant) 	| :heavy_check_mark: 	|
| Open litter map                    	| 11             	| 187                            	| > 100k     	| Multilabel classification 	| Waste in the wild                    	| [website](https://openlittermap.com/)                                          	| :heavy_check_mark: 	|
| Litter                             	| 24             	| size, shape, or material       	| ~14 000    	| Detection                 	| Waste in the wild, paid license      	| [website](https://www.imageannotation.ai/litter-dataset)                       	| :heavy_check_mark: 	|
| Drinking Waste Classification      	| 4              	| -                              	| 9640       	| Detection                 	| Clear background, (cans and bottles) 	| [kaggle](https://www.kaggle.com/arkadiyhacks/drinking-waste-classification)   	| TO-DO 	|
| waste_pictures                     	| 34             	| -                              	| ~24 000    	| Classification            	| Scraped from google search           	| [kaggle](https://www.kaggle.com/wangziang/waste-pictures)                     	| TO-DO 	|
| spotgarbage                        	| 3              	| -                              	| ~2 400     	| Classification            	| Scraped from google search           	| [kaggle](https://www.kaggle.com/apremeyan/garbage)                            	| TO-DO 	|
| DeepSeaWaste                       	| 5              	| -                              	| 3 055      	| Classification            	| Underwater images                    	| [kaggle](https://www.kaggle.com/henryhaefliger/deepseawaste)                  	| TO-DO 	|

# Description

## TrashCan 1.0

An Instance-Segmentation Labeled Dataset of Trash Observations

7212 images under 3 main categories: bio, trash, unknown.
Categories:
* bio = turtle, squid, lobster, unknown, jellyfish, stingray, shrimp, crawfish, octopus, shark, shell, crab, starfish, eel
* trash = clothing, pipe, bottle, bag, snack_wrapper, glove, tire, can, cup,container, branch, wreakage, tarp, box, hose, rope, hay, net, paper, bucket, wire
* unknown
**Download**: Directly from website  https://conservancy.umn.edu/handle/11299/214865

# Trash-ICRA19:
A Bounding Box Labeled Dataset of Underwater Tras
5,700 underwater images extracted from video
https://jungseokhong.github.io/

**Download**: Directly from website https://conservancy.umn.edu/handle/11299/214366

![](img/icra_example.GIF)


## TACO
Open dataset with 1500 images from 28 categories and 60 detailed sub-categories of waste in the wild. Annotations available in COCO-json.

**Download**: Directly from website http://tacodataset.org/

![](img/taco_example.jpg)

## TACO bboxes
WIP
**Download**: Directly from website http://tacodataset.org/

## UAVVaste
**Drone rubbish detection intelligent technology**
The UAVVaste dataset consists to date of 772 images and 3716 annotations. The main motivation for creation of the dataset was the lack of domain-specific data. The datasets that are widely used for object detection evaluation benchmarking. The dataset is made publicly available and is intended to be expanded.

annotations [Detection] Segmentation]- https://github.com/UAVVaste/UAVVaste [drone]
**Download**: Directly from annotations json on github https://github.com/UAVVaste/UAVVaste
![](img/uavvaste_example.gif)

## Trashnet
The dataset spans six classes: glass, paper, cardboard, plastic, metal, and trash. Currently, the dataset consists of 2527 images:

* 501 glass
* 594 paper
* 403 cardboard
* 482 plastic
* 410 metal
* 137 trash

**Download**: Directly from github https://github.com/garythung/trashnet

also is known as **Garbage Classification Data**

The Garbage Classification Dataset contains 2467 images from 6 categories: cardboard (393), glass (491), metal (400), paper(584), plastic (472) and trash(127).

**Download**: Directly from kaggle https://www.kaggle.com/asdasdasasdas/garbage-classification

![](img/trashnet_example.jpg)

## Plastic Waste DataBase of Images – WaDaBa
4000 images with detailed description of a plastic type (PET, PP, PE-HD...), object color, deformation level, dirtiness  and others. [classification]

The object were put on the research position and next photographed with first and second type of light. There were series carried out of 10 photographs with differ in the angle of the turnover for every object (in the vertical axis). Next the object was damaged to varying degrees: small, medium and large. For each type of destruction have been made 10 photographs. So considering all variants for every object 40 photographs were taken, multiplying it by the number of objects, 4 000 of photographs were created in the database.

**Download**:  Images free-to-download directly from website. Annotations available after signing license http://wadaba.pcz.pl/#download

![](img/wadaba_example.jpeg)


## GLASSENSE-VISION
Home-supplies classification. It is not strict litter dataset but it gathers over 2000 images with objects well-spareted from background. Covers 7 main categories of (Banknotes, Cereals, Medicines, Cans, Tomato sauces, Water bottle, Deodorant stick) and 136 subcategories.

Glassense-Vision is a set of data we acquired and annotated to the purpose of providing a quantitative and repeatable assessment of the proposed method. The dataset includes 7 different use cases, meaning different object categories, where for each one of them we provide training (reference images used also to build dictionaries) and test images. All images in the dataset are manually annotated. The different use cases (object categories) can be grouped in three main geometrical types:

**Download**: http://www.slipguru.unige.it/Data/glassense_vision/

![](img/glassense_example.jpg)

## Waste Classification data
Over 25k images already divided into training data - 22564 images and test data - 2513 images. Two main categories: Organic and recyclable

**Download**: Directly from kaggle https://www.kaggle.com/techsash/waste-classification-data

![](img/waste_example.jpg)


## Waste Classification Data v2
A variation about the **Waste Classification data**: extended by the new category "N" - Nonrecyclable added.

Over 25k images already divided into training data - 22564 + 2508 (N) images and test data - 2513 images + new 397 from category nonrecyclable. Three main categories: Organic (O) and recyclable  (R), and nonrecyclable (N). TRAIN folder contains 2508 images in the "N" directory.
The TEST folder contains 397 images in the "N" directory.

**Download**: Directly from kaggle https://www.kaggle.com/sapal6/waste-classification-data-v2

## Open litter map
The biggest dataset with over 100k images in total with 11 main categories and 187 subcategories.[multilabel] [classification]
https://openlittermap.com/

**Download**: Only from json with scraper -  [detectwaste scraper](https://github.com/wimlds-trojmiasto/detect-waste)

![](img/trashnet_example.jpg)

## Litter

The Litter dataset contains 14k images with 20k annotations (bounding boxes) and 24 classes. Each class represents an object (cup), while subclasses determine its size, shape, or material (long paper cup/short paper cup).

**Download**: After buying a license https://www.imageannotation.ai/litter-dataset

![](img/litter_example.jpg)


## Drinking Waste Classification
TO-DO

## waste_pictures
TO-DO

## spotgarbage
TO-DO

## DeepSeaWaste
TO-DO
