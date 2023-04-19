# NLP_CodeSearch
代码搜索模型
## Dependency
> Tested in Ubuntu 16.04
* Python 2.7-3.6
* Keras 2.1.3 or newer
* Tensorflow-gpu 1.7.0
* lucene 7.7.1


## usage

   ### dataset
  The datasets used in our paper will be found at: https://drive.google.com/drive/folders/1QJi-fRBTfyecRufDQVfSGN7GzgEt-0kx?usp=sharing
  
   
   
   #### Configuration
   Put the data set into the `data/github` directory under `keras`
   
   Edit hyper-parameters and settings in `config.py`
   
   #### Train and Evaluate
   
   ```bash
   python main.py --mode train
   python main.py --mode eval
