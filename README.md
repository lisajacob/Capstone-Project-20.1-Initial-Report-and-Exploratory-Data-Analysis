### Classification of Lunar Rocks

**Lisa Jacob**

#### Executive summary

#### Rationale
One of the goals of computer vision is to give machines the ability to interpret visual scenes. For space robotics, the lunar lander and the rover has to be able to autonomously navigate. Thus its ability to understand the rock size-frequency distribution (RSFD) on lunar surfaces is important. Large rocks within a landing site represent potential hazards to landers as well as navigational threat to rovers. 

#### Research Question
The research for this Capstone project focuses on Semantic Segmentation of rocks on the lunar surface with the ultimate goal to distinguish between small rocks, large rocks, small craters, and large craters on the lunar surface. 

#### Data Sources
Kaggle dataset [Artificial Lunar Rocky Landscape](https://www.kaggle.com/datasets/romainpessia/artificial-lunar-rocky-landscape-dataset)

#### Methodology
For this project, I will be using ResNeXt, which is a Convolutional Neural Network (CNN) architecture that was developed by Microsoft Research and introduced in 2017 in a paper titled [Aggregated Residual Transformations for Deep Neural Networks](https://ieeexplore.ieee.org/document/8100117)
This project will utilize PyTorch which has the following model builders in Torchvision tool to instantiate a ResNeXt model.
resnext50_32x4d (*[, weights, progress])
resnext101_32x8d (*[, weights, progress])
resnext101_64x4d (*[, weights, progress])

#### Results
Out of the 4 classes, the semantic segmentation module successfully found 2 classes. The algorithm needs to be improved to find all 4 classes with very little loss.

#### Next steps
Augment the dataset with transformations and compare difference architectures

#### Outline of project

- [Exploratory Data Analysis]()
- [Initial pass at algorithm development]()

##### Contact and Further Information
For further information, send an email to lisa.jacob@gmail.com