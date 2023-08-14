## CNN for image classification

This notebook presents a complete lifecycle of CNN neural network for image classification with Pytorch

------
The chosen dataset is called CIFAR-10
This dataset includes 32x32 RGB images, each image with an different object  
The objects can be: Airplane, Car, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck  
For transforming it into labels they have an alias from 0 to 9 in alfabetical order, as the below.  
labels = {'plane': 0,  
    'car': 1,  
    'bird': 2,  
    'cat': 3,  
    'deer': 4,  
    'dog': 5,  
    'frog': 6,  
    'horse': 7,  
    'ship': 8,  
    'truck': 9  
}  
The train dataset has 60000 images and for test dataset we have 10000 images

--------
The dataset select can be downloaded at Pytorch dataset To download the dataset set download=True parameter inside datasets.MNIST funcition  

train_data = datasets.MNIST(root='./Data', train=True, download=True)  
test_data = datasets.MNIST(root='./Data', train=False, download=True)
