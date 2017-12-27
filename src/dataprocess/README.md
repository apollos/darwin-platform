# We need an abstract class to define all data loading and data transfer operation:
## 1. data loading
### a) load data from lmdb
### b) load data from tensorrecord
### c) load data from csv file
### d) load data from txt file
### e) load data from image file
### f) load data from xml file 

## 2. separate data
### a) An abstract class for separation action
### b) implement same distribution hand-out, cross-sample, uniform-sample

## 3. data queue management
### Need consider tensorflow queue method and native queue method

## 4. data store
### a) store data to lmdb
### b) store data to tensorrecord
### c) image to image
### d) image to vector
### e) word to vector
