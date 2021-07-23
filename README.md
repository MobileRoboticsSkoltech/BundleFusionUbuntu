# BundleFusionUbuntu
This fork from [FangGet/BundleFusion_Ubuntu_Pangolin](https://github.com/FangGet/BundleFusion_Ubuntu_Pangolin) which is Ubuntu version of BundleFusion, based on [niessner/BundleFusion](https://github.com/niessner/BundleFusion). 

Some changes were made to be able to build a run the code with the latest libraries on Ubuntu 20.04 / Linux Mint 20.2

## Requirements 

TBD

## Building

```
cd BundleFusionUbuntu
mkdir build
cd build
cmake ..
make -j8
```

## Usage

* Download datasets from BundleFusion project mainpage [http://graphics.stanford.edu/projects/bundlefusion/](http://graphics.stanford.edu/projects/bundlefusion/) and unzip it.
* Run Commands:

```
cd BundleFusionUbuntu
cd build
./bundle_fusion_example ../zParametersDefault.txt ../zParametersBundlingDefault.txt /PATH/TO/dataset/office2
```
