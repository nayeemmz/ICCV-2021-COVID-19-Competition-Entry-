# ICCV-2021-Workshop-MIA-COV19D-TeliNet

This repository is the code for entry to ICCV 2021 Workshop: MIA-COV19D, https://mlearn.lincoln.ac.uk/mia-cov19d/.

This code classifies CT Scan COVID-19 images as covid and non-covid using a four layer Convolutional Neural Network.

## Getting Started

Clone this repository using 

``` 
git clone https://github.com/nayeemmz/TeliNet.git 
```
 
$ ./tree-md .
The data directories structure should be 

 
 * ``` 
 [train](./train)
 ```
   * [covid](./train/covid)
   * [non-covid](./train/non-covid)
 * [validation](./validation)
   * [covid](./validation/covid)
   * [non-covid](./validation/non-covid)
 * [test](./test)
   * [to_be_predicted](./test/to_be_predicted)
  
