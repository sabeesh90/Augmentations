# Augmentations
The repository consists of implementation of augmentation techniques in tensorflow and pytorch

## Tensorflow
The tensorlow implementation is currently in progress

## Pytorch
There are two ways to go about this.
### Individual Images
The steps involved are
1) cv2.imread() - to read the images
2) cv2.cvtColor() -  to convert native bgr to rgb color
3) Normalize using transforms.Compose + Applying augmentations
4) Transpose using np.transpose(augmented_image, (1,2,0))
5) Plot images

### Dataloader Images
1) Create dataset
2) Create an instance of iteration
3) next iter the instance
4) Plot images

![download](https://user-images.githubusercontent.com/48343095/152729845-2e7c6e0e-66d3-4bda-8b32-fa8e3fc720d8.png)
