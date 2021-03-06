# RACE Reading Comprehension Task

Code for the paper:

[RACE: Large-scale ReAding Comprehension Dataset From Examination](https://arxiv.org/pdf/1704.04683.pdf). Guokun Lai*, Qizhe Xie*, Hanxiao Liu, Yiming Yang and Eduard Hovy.

## Dependencies
* Python 2.7
* Theano >= 0.7
* Lasagne 0.2.dev1

## Datasets
* RACE:
    Please download from [here](http://www.cs.cmu.edu/~glai1/data/race/) then create a "data" directory in the root directory and decompress the file in the "data" directory

* Word embeddings:
    * glove.6B.zip: [http://nlp.stanford.edu/data/glove.6B.zip](http://nlp.stanford.edu/data/glove.6B.zip)

## Usage
### Preprocessing
    * python preprocess.py

### Stanford AR
    * train: bash train_SAR.sh
    * test: bash test_SAR.sh

### GA
    * train: bash train_GA.sh
    * test: bash test_GA.sh

## Reference
```
@article{lai2017large,
  title={RACE: Large-scale ReAding Comprehension Dataset From Examinations},
  author={Lai, Guokun and Xie, Qizhe and Liu, Hanxiao and Yang, Yiming and Hovy, Eduard},
  journal={arXiv preprint arXiv:1704.04683},  
  year={2017}
}
```

## Thanks
* The code is adapted from https://github.com/danqi/rc-cnn-dailymail and https://github.com/bdhingra/ga-reader

## Contact
* Please contact Qizhe Xie (qzxie AT cs DOT cmu DOT edu) if you find bugs or missing info

## License
MIT
