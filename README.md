 ### Transfer-Learning
 
 Transfer Learning(TL) is a research problem in ML,DL that focus on storing knowledge gained while solving one problem and applying it to a different but related problem. 
 
 For example: Knowledge gained while learning to recognize cars could apply when trying to recognize trucks, basic features for example: the steerng, wheels, and some of the other components between car and the truck are similar. So, we can use the knowledge of this visual word to transfet the knowledge into solving different problems.
 
By using the google trained mobilenet v2 model which is trained on 1.4 million images and total thousand [classes](ImageNetlabels.txt).

 We classify the flower dataset using this model with 94% accuracy. 

#### Dataset and Model:

**Flower dataset:** [click here.]("https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz")

**Mobilenet V2:** [click here.]("https://tfhub.dev/google/tf2-preview/mobilenet_v2/classification/4")
**Mobilenet V2 Model Feature Vector:** [click here.]("https://tfhub.dev/google/tf2-preview/mobilenet_v2/feature_vector/4")
