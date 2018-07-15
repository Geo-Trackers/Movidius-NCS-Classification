# Movidius-NCS-scripts
This repo contains set of scripts for the running classification & benchmarking with Movidius NCS. 

Clone this repository inside the sample directory and run the below commands for Image Classification using Movidius NCS

Example Usage: 

# Example USAGE

Using Pretrained Squeezenetgraph

python movidius_ncs_classify.py --graph graphs/squeezenetgraph --dim 227 --labels synset_words.txt --image images/car.jpg 



<img width="838" alt="screen shot 2018-07-15 at 8 26 56 pm" src="https://user-images.githubusercontent.com/7304644/42734414-caeafac4-886d-11e8-8d85-cd5211fd91f1.png">


You may also want to try using Googlenetgraph:

python movidius_ncs_classify.py --graph graphs/googlenetgraph --dim 224 --labels synset_words.txt --image images/car.jpg









Referenced from pyimagesearch tutorials @https://www.pyimagesearch.com/2018/02/12/getting-started-with-the-intel-movidius-neural-compute-stick/


