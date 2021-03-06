
# ADTFK

Codes for WWW 2022 paper [Dual Fine-Grained Knowledge Transfer for Cross-Domain Recommendation].


## Requirement
* Python 3.6
* Tensorflow 1.10.0
* Numpy


## Files in the folder
- `model/`
    - `ADTFK.py`: detail implementation of ADTFK, training process and evaluation
- `data/`: four cross-domain recommendation tasks based on two widely used datasets Amazon and Douban
    - `Amazon/Cell_Elec/`
    - `Amazon/Movie_Music/`
    - `Douban/Movie_Book/`
    - `Douban/Music_Book/`
- `load_data.py`: defining the class of datasets
- `utils.py`: constructing training set and testing set for cross-domain scenario
- `params.py`: some parameters and directions concerned with the model


## Running the code
1. Modify the `DATASET`, `metaName_1`, `metaName_2` in `params.py` to set certain cross-domain recommendation task

2. run python ADTFK.py.
