# LRP_argmax

Keras implementation of the argmax-rule for LRP proposed in https://link.springer.com/chapter/10.1007/978-3-030-30179-8_16. 
Based on the INNvestigate repository https://github.com/albermax/innvestigate.

# Usage
If you have a keras model `model` you can create an INNvestigate analyzer for your model with
```
analyzer = argmax_analyzer.Argmax(model)
```
A saliency map for a given `input` can then for example be created by using 
```
analyzer.analyze(input)
```
For furhter details please refer to the original innvestigate repository https://github.com/albermax/innvestigate.
