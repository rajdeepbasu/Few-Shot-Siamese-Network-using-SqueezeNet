# One-Shot-Siamese-With-SqueezeNet

### What is One Shot Learning?

One-shot learning is an object categorization problem, found mostly in computer vision. Whereas most machine learning based object categorization algorithms require training on hundreds or thousands of samples/images and very large datasets, one-shot learning aims to learn information about object categories from one, or only a few, training samples/images.

#### What is a Siamese Network ?   

Siamese networks (Bromley, Jane, et al. “Signature verification using a” siamese” time delay neural network.” Advances in neural information processing systems. 1994.) are neural networks containing two or more identical subnetwork components. A siamese network may look like this:

![SiameseNetwork](https://miro.medium.com/max/968/1*hBJRs10uBc9a2Ol10N-jlg.png)

It is important that not only the architecture of the subnetworks is identical, but the weights have to be shared among them as well for the network to be called “siamese”. The main idea behind siamese networks is that they can learn useful data descriptors that can be further used to compare between the inputs of the respective subnetworks.

#### What is SqueezeNet?

SqueezeNet is the name of a deep neural network for computer vision that was released in 2016. SqueezeNet was developed by researchers at DeepScale, University of California, Berkeley, and Stanford University. In designing SqueezeNet, the authors' goal was to create a smaller neural network with fewer parameters that can more easily fit into computer memory and can more easily be transmitted over a computer network.  

![SqueezeNet Architecture](https://www.researchgate.net/publication/335357358/figure/fig4/AS:795145175842817@1566588791117/The-architecture-of-SqueezeNet-11.ppm)

Siamese Base Network - [Harshvardhan Gupta's Repo](https://github.com/harveyslash/Facial-Similarity-with-Siamese-Networks-in-Pytorch)  
Early Stopping Code - [Stefano Nardo's Repo](https://gist.github.com/stefanonardo/693d96ceb2f531fa05db530f3e21517d#file-early_stopping-py)  
