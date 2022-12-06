# Image-Enhancement-using-Nature-Inpired-Algorithms
This repository contains the Python code for applying nature-inspired techniques to improve the contrast of MRI pictures. Ant colony optimization, genetic algorithms, and simulated annealing are examples of nature-inspired techniques that create a global transfer function to transform input images into greater contrast ones while attempting to preserve the natural appearance of the images.

## Description
The technique creates a transfer function that may be used to transform any picture into one with enhanced contrast by scattering a few artificial agents, often known as artificial ants, throughout a search region. The ants go from the transfer function's origin (bottom left) to its top right point. Any ant will probabilistically select one of the following movement choices from those that are accessible to it.
A transfer function is built and its fitness is assessed after arriving at the final location. Pheromones are left behind on the ants' trail depending on how well a transfer function works. The likelihood that an ant will choose to pass over a place while it is close improves when a pheromone is applied to it.
Every artificial ant created has a unique genetic code. Through the use of genetic algorithms, ant populations develop. The ants' features and preferred routes through the search area are altered as a result. The simulated annealing then makes an attempt to fine-tune the optimal transfer functions using an artificial annealing process.
After this process is finished, the best transfer function is selected and is used to convert the input image.
For more details of the image enhancer method read the paper given in the repo. 
