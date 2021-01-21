# ActivationFunctions using Custom Layers in Keras
[![GitHub stars](https://img.shields.io/github/stars/UROP-X/ActivationFunctions)](https://github.com/UROP-X/ActivationFunctions/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/UROP-X/ActivationFunctions)](https://github.com/UROP-X/ActivationFunctions/network)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![GitHub license](https://img.shields.io/github/license/UROP-X/ActivationFunctions)](https://github.com/UROP-X/ActivationFunctions/blob/master/LICENSE)




Activation functions are an important are of deep learning research .Many new activation functions are being developed ,these include *bio-inspired* activtions, *purely mathematical activation functions* including others . Despite, such advancements we usually find ourselves using RELU and LeakyRELU commonly without using/thinking about others.
In the following notebooks I showcase how easy/difficult it is to port an activation function using **Custom Layers in Keras and Tensorflow!**


Link to main notebook --> [Activations.ipynb](https://github.com/Agrover112/ActivationFunctions/blob/master/src/Activation-Functions(GELU%2CSELU%2CELU%2CLeakyReLU%2CPRELU).ipynb)

### Implemented activations:
 
- LeakyReLu
- ParametricReLu
- Elu
- SElu
- Swish
- GELU

Some Metrics:
| Activation   |    Time-1Layer     |  Time-nLayer | Time(with multiprocessing) |Time(without) |
|----------|:-------------:|------:|------:|------:|
| LeakyReLu |  left-aligned |------:|23.443861722946167|24.17226767539978|
| Elu |    centered   |   $12 |  $12 ||
| Selu | right-aligned |    $1 |  $1 ||
| Gelu |  |    $1 |  23.319090604782104|23.577461004257202|
| Swish | right-aligned |  | 23.77716302871704 |23.70854926109314|
### Structure
 ```  
src
|
|-- Activations.ipynb
|-- utils
      |-- Utils.ipynb
      |-- utils.py
      
references
|
|--Ref1
|--Refn

```

###  Usage
 ``` 
 git clone  https://github.com/Agrover112/ActivationFunctions.git
```

### References
- [References:D](https://github.com/Agrover112/ActivationFunctions/tree/master/references)
