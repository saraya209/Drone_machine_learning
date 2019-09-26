# High Resolution Soil Moisture Prediction Using Machine Learning and Unmanned Aircraft Systems-Based Remote Sensing

[![Lab Website](https://github.com/saraya209/soil_ksat/blob/master/imgs/ucmerced_25.png)](http://soilphysics.ucmerced.edu "Soil Physics @ UC Merced")
[![Twitter](https://github.com/saraya209/soil_ksat/blob/master/imgs/Twitter_Social_Icon_Square_Color_33.png)](https://twitter.com/SamuelA209 "@SamuelA209")

Pending the publication of this work in a peer-reviewed journal, this repository will host the machine learning models, training data, and R scripts used to build the models that predict topsoil moisture from surface properties remotely sensed by unmanned aircraft system (drone). Detailed description of this work is available on the fourth chapter of [my dissertation](https://escholarship.org/uc/item/23d272xg#page=87).

## Highlights

### Drone remote sensing
![](https://github.com/saraya209/Drone_machine_learning/blob/master/ad/topo_variables.jpg)

In addition to reflectance in four separable bands, a high-resolution digital surface model was developed from the drone-based multispectral imaging and used to develop tens of topographic parameters.

### Reproducible and efficient coding
[![](https://github.com/saraya209/Drone_machine_learning/blob/master/ad/dependency_snip.png)](http://htmlpreview.github.io/?https://github.com/saraya209/Drone_machine_learning/blob/master/ad/Plan_GBM_Drake.html)

The model testing and tuning scripts were done using [`drake`](https://ropenscilabs.github.io/drake-manual/) R package which ensures  reproducibility and efficiency. *Click the image to explore a sample dependency graph of a script that produces a model report.*

### Model analysis and interpretation
[![](https://github.com/saraya209/Drone_machine_learning/blob/master/ad/variable_effect.png)](http://htmlpreview.github.io/?https://github.com/saraya209/Drone_machine_learning/blob/master/ad/gbm_62_analysis.html)

The developed models were analyzed and compared detailed reports produced. *Click the image to explore a sample report for one iteration of a boosted regression tree model.*
