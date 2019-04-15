# Object detection with tensorflow API
## https://medium.com/@patrickhk/the-only-and-easy-object-detection-tensorflow-api-guide-you-need-c78037f03f2a

The Easiest Object Detection Tensorflow API tutorial you need.
This guide will demonstrate how to use the Tensorflow Object detection API with pre-trained model to detect and identify objects in webcam.

![1_7ambzpeul77d4zw4cazshq](https://user-images.githubusercontent.com/38428076/48075617-9fa3ab80-e21e-11e8-8673-bc26b703f756.jpeg)
The detector says it is a dog, would you consider this as the negative result ? <br/>
Honestly I think it is very hard for the model to classifier it as a doll/toy unless you purposely feed in so many this kinds of images with “doll” label, but this may create false detection to real dog object.<br/>


![2](https://cdn-images-1.medium.com/max/800/1*7Eik9f8HOvUYrR1frAqm3g.jpeg)
It should be a lion/toy but is now classified as Teddy Bear. <br/>
This is because we just use the pre-trained ssd model with coco dataset. <br/>
There are 90 classes in the pre-trained data but doesnt contain a class called “lion”. <br/>
I myself think this model is good enough as it classified the lion toy to the closest class, teddy bear<br/>
