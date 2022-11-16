### SEMANTIC SEGMANTATION BASED ON DEEP LEARNING TO MAP CROP TYPES IN SATELLITE IMAGERY

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#get-the-data">Get the Data</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The food necessities of a country are mainly determined by its agricultural resources. Crop type mapping is therefore required for a wide range of applications in agricultural monitoring and food security. Different techniques have been used to collect this information. The possibility of creating crop-type maps becomes more prominent with the availability of remote sensing imagery and deep learning algorithms. In this context, the purpose of this work is to apply and evaluate deep learning algorithms for crop-type mapping in agricultural fields along South Africa’s Orange River. It is a very diverse zone with a wide variety of crops (such as cotton, maize, grass, Lucern, Pecan, Vacant, and Vineyard). As a result of this heterogeneity, crop-type discrimination became more challenging. For such a task, four models including U-Net, MobileNetv2- UNet, ResNet50-UNet, and DeepLabv3 are used and evaluated on a dataset provided by Zindi in 2017, the largest network for data scientists in Africa, during the crop growing period that starts from March to August. The data were pre-processed using the normalized difference vegetation index (NDVI), and the adjusted-soil vegetation index (SAVI). The performance of models is assessed using the kappa coefficient (k), the mean Intersection Over Union(mIOU), the F1 score (F1), and the confusion matrix.
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Get the Data

You can register an account on https://zindi.africa/ and download the data from the Zindi competition: Farm Pin Crop Detection Challenge.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Installation
* Rasterio
  ```sh
  !pip install -q rasterio

* Geopandas
  ```sh
  !pip install -q geopandas

* Focal Loss
  ```sh
  !pip install focal-loss

* Other
  ```sh
  !pip install git+https://github.com/tensorflow/examples.git
  !pip install -U tfds-nightly
  ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

