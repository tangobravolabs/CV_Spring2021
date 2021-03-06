# CV_Spring2021

04.12.21
https://www.youtube.com/watch?v=HKnY05QoSi0
https://www.youtube.com/watch?v=oXlwWbU8l2o
https://alwaysai.co/blog/computer-vision-on-edge-vs-cloud
* Edge computing, on the other hand, is a form of distributed computing where all computations occur outside of the cloud, or at the “edge” of a centralized server. 
* Edge has greater reach and is faster. The edge has no dependency on a central data center or network bandwidth, allowing for computer vision operations in remote locations that lack the necessary network infrastructure and faster response times. This enables the development of new IoT technologies in industries such as agriculture, waste management, and human search & rescue. This also supports more time-sensitive use cases such as robotic surgery, autonomous driving and human fall detection
* Edge is less risky and more private. Edge computing distributes the risk of exposure across multiple devices, and can perform all processing disconnected from a central server - a more secure and private architecture. For example, edge devices can be installed inside of a person’s home, process real-time data and act on that data without relying on a shared cloud service that could compromise the privacy of their day-to-day activity.
* Edge is significantly less expensive. Computer vision is a powerful technology, but complex and can become very expensive to build, deploy and maintain. For example, cloud companies charge for inferencing per endpoint, per minute. This may help organizations that want to pay on an ‘as needed’ basis; but becomes enormously burdensome for organizations that demand large amounts of real-time processing - such as a smart city or hospital with many cameras and sensors running 24 hours a day.
* 

04.11.21
https://www.cs.washington.edu/research/graphics

Books:
* https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf
* https://www.eecs.yorku.ca/~mbrown/ICCV19_Tutorial_MSBrown.pdf
* > Due to the accumulation effect of the cones, two different SPDs can be perceived as the same color (such SPDs are called "metamers").
* > Grassman’s Law states that a source color can be matched by a linear combination of three independent “primaries”. 
* > Radiometry: Measures either light coming from a source (radiance) or light falling on a surface (irradiance)
* > Photometry/ colorimetry: Quantitative measurement of perceived radiant energy based on human’s sensitivity to light
* > Stevens' model stated that human perception to brightness followed a cube-root power-law.
* Typical image processing pipeline
* > ISO gain and raw-image processing
* > RGB Demoasicing
* > Mapping to sRGB output
* > Color Manipulation
* > White-Balance & Color Space Transform
* > Jpeg compression
* > Save to file
* Mistakes made early in the camera pipeline are propagated.
* https://courses.cs.washington.edu/courses/cse576/20sp/
* 

04.10.21
https://heartbeat.fritz.ai/6-significant-computer-vision-problems-solved-by-ml-623eb50544c5
* https://heartbeat.fritz.ai/6-significant-computer-vision-problems-solved-by-ml-623eb50544c5
Image classification is the first computer vision task to be tackled by machine learning—in the 1950s, the perceptron algorithm was implemented in the Mark 1 Perceptron machine, which was used for image classification
And in the case of using more than 2 classes (ex: digits, animals, vehicles, etc.), the problem is deemed a multi-class classification problem, for which the last layer will contain n neurons (n = Number Of Classes) with a softmax activation function.
Currently, one of the most significant datasets is ImageNet, which consists of 1M samples of 1K classes of different animal species. This dataset is really important for image classification for two reasons.
First, It’s used as a benchmark for evaluating new network architectures through a yearly competition active from 2010 until 2017 and is still used for evaluating of new subsequent architectures.
And second, it’s widely used to set pre-trained weights of other networks, as this dataset is so variant it can teach networks to detect important features in images that can be used in other computer vision tasks.
There are a lot of other datasets for image classification that have been used repeatedly through research—such as STL-10, CIFAR-10, and CIFAR-100—in a manner similar to ImageNet, but with less data and smaller image sizes.
As for medical research, a lot of datasets have been developed for different specific tasks such as ISIC, MURA, and DermNet. Medical datasets are harder to collect which is challenging for complicated tasks, as most of the time it’s not very feasible to collect large datasets when needed.
Models
http://yann.lecun.com/exdb/lenet/
https://arxiv.org/abs/1409.1556
https://arxiv.org/abs/1409.4842
https://arxiv.org/abs/1512.03385
https://arxiv.org/abs/1704.04861
Object localization and detection is a computer vision problem in which, given an image, the algorithm has to decide the locations of one or more target objects, outputting bounding boxes for each that appears in the image or video frame.
And to localize the object, the network outputs four variables representing the bounding box, which can be (x, y, w, h), with the x, y representing either the center or the top right corner of the bounding box.
COCO, PASCAL, and ImageNet datasets are considered the main datasets used for evaluating new object detection architectures. 
https://en.wikipedia.org/wiki/Region_Based_Convolutional_Neural_Networks
https://arxiv.org/abs/1506.02640
https://arxiv.org/abs/1512.02325
Image segmentation is used in various applications (medical, robotics, satellite imagery analysis, etc.) to not only understand the locations of objects in images and video frames, but to more precisely map the boundaries between different objects in the same image.
For semantic segmentation, the solution requires objects’ pixels for each class of targets in the image to be labeled with the same value. 
Meanwhile, instance segmentation requires separating different instances of the same class by assigning their pixels different values. Some approaches handle the occlusion of objects so that the occluded part of the object is also represented.
 COCO and PASCAL datasets are two of the largest datasets for image segmentation, using general objects, as mentioned earlier.
Other datasets are built for more specific applications. For medical applications, there are a lot of datasets such as BraTS and Lits, which target tasks like tumor segmentation in different parts of the body and different types of diseases. Datasets like SpaceNet and the Agriculture-Vision Database consist of satellite images, which can have a variety of applications used for labeling large-scale things like streets, buildings, water bodies, etc.
https://arxiv.org/abs/1505.04597
https://arxiv.org/abs/1703.06870#:~:text=The%20method%2C%20called%20Mask%20R,CNN%2C%20running%20at%205%20fps.
Data Generation
By learning the distribution of a dataset using approaches like GANs, we can generate new images that look real and can be used in new datasets. For example, by going to the following website, you will see a new picture of a person that looks real—but has just generated by a CNN.
Domain Adaptation
Approaches like GANs and VAEs can be used to transform images from a source domain (street view in summer) to a target domain (street view in winter), which is very beneficial for generalizing networks’ performance on different tasks without annotating new data. This is also used for cool applications like deepfakes.
Neural Style Transfer		
Another cool application of CNNs is neural style transfer, which uses a content image and a style image to output an image with the same content of the content image, but with the style of the style image. Using this, we can transform normal pictures into version that appear to be created by Van Gogh or Picasso.
	



4.09.21
* https://towardsdatascience.com/the-4-step-guide-to-becoming-a-computer-vision-expert-in-2020-8e821514e2a7
* The steps I’ll talk about is not something one can master in 1 month to prepare for the next interview. But these will help you to really get into the domain over a course of 4–9 months depending upon your passion.
* Theory
* * https://www.coursera.org/learn/machine-learning
* * https://www.coursera.org/specializations/deep-learning
* * http://cs231n.stanford.edu/
* * https://www.udacity.com/course/computer-vision-nanodegree--nd891
* * http://deep%20learning%20in%20computer%20vision/
* Competitions
* * https://www.kaggle.com/
* * https://www.aicrowd.com/
* * https://codalab.org/
* * https://mlcontests.com/
*  Personal Projects
* * Recruiters are more and more focusing on your projects to gauge your capabilities. And in this case, what you are doing is much more important than how well you are doing it. Just to clear up, getting 50% accuracy on an interesting problem on a messy dataset is much better than getting 99.98% accuracy on MNIST.
* * Create an elaborate notebook on any problem on a dataset. Better yet create a set of notebooks in a repository tackling different sets of problems or using different sets of approaches on the same dataset
* * Develop a small package that you think will be useful. It does not have to be pathbreaking but just has to make something easier. It will give you a lot of insight into designing and writing code that people can use. Host it on pip if you like. That’s an added star on the collar.
* Research Papers
* Extra Insights
* https://towardsdatascience.com/maximize-your-gpu-dollars-a9133f4e546a
* 

04.08.21
https://machinelearningmastery.com/what-is-computer-vision/
* To get the most out of image data, we need computers to “see” an image and understand the content.
* This is a trivial problem for a human, even young children.
* Computer vision is a field of study focused on the problem of helping computers to see.
* The goal of computer vision is to understand the content of digital images. Typically, this involves developing methods that attempt to reproduce the capability of human vision.
* Image processing is the process of creating a new image from an existing image, typically simplifying or enhancing the content in some way. It is a type of digital signal processing and is not concerned with understanding the content of an image.
* Computer vision seems easy, perhaps because it is so effortless for humans.
* One reason is that we don’t have a strong grasp of how human vision works.
* Another reason why it is such a challenging problem is because of the complexity inherent in the visual world
* A given object may be seen from any orientation, in any lighting conditions, with any type of occlusion from other objects, and so on. A true vision system must be able to “see” in any of an infinite number of scenes and still extract something meaningful.
* Computers work well for tightly constrained problems, not open unbounded problems like visual perception.
* Optical character recognition (OCR)
* Machine inspection
* Retail (e.g. automated checkouts)
* 3D model building (photogrammetry)
* Medical imaging
* Automotive safety
* Match move (e.g. merging CGI with live actors in movies)
* Motion capture (mocap)
* Surveillance
* Fingerprint recognition and biometrics
* Object Classification: What broad category of object is in this photograph?
* Object Identification: Which type of a given object is in this photograph?
* Object Verification: Is the object in the photograph?
* Object Detection: Where are the objects in the photograph?
* Object Landmark Detection: What are the key points for the object in the photograph?
* Object Segmentation: What pixels belong to the object in the image?
* Object Recognition: What objects are in this photograph and where are they?
* 

04.07.21
https://cloud.google.com/vision/docs/drag-and-drop
* Google API allows a drag and drop test drive feature
* Comes back with obeject detection and confidence
* Comes back with top labesl and confidence (interesting relationship between things)
* Comes back with colors and % of image
* Comes back with safe search issue confidences
Also, https://experiments.withgoogle.com/collection/ai
* https://pose.yee.gd/
* https://experiments.withgoogle.com/ai/melody-mixer/view
* https://experiments.withgoogle.com/alto

04.06.21
https://web.stanford.edu/class/cs231a/project.html
* Applications. If you're coming to the class with a specific background and interests (e.g. biology, engineering, physics), we'd love to see you apply computer vision to problems related to your particular domain of interest. Pick a real-world problem and apply the techniques covered in the class (or even beyond the class) to solve it!
* Models. You can build a new model (algorithm) for computer vision, or a new variant of existing models, and apply it to tackle vision tasks. This track might be more challenging, and sometimes leads to a piece of publishable work. Talk to the course staff if you would like to pursue this route for more ideas!
* Visual desciptionProject Proposal
* > The project proposal should be up to 2 pages and should contain the following:
* > What is the problem that you will be investigating? Why is it interesting?
* > What data will you use? If you are collecting new datasets, how do you plan to collect them?
* > What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations?
* > What reading will you examine to provide context and background?
* > How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g. what performance metrics or statistical tests)?
* > By what dates will you complete certain parts of your project? List specific goals for the midterm progress report.
* http://www.cv-foundation.org/openaccess/CVPR2016.py


04/02/21
TIL: https://clearpathrobotics.com/heron-unmanned-surface-vessel/
* Robotic Sensors:
* > Camera
* > Thermal Camera
* > LiDAR
* > GPS
https://www.verywellmind.com/what-are-monocular-cues-2795829
* One way that we perceive depth in the world around us is through the use of what are known as monocular cues. These are clues that can be used for depth perception that involve using only one eye. 
* The relative size of an object serves as an important monocular cue for depth perception. It works like this: If two objects are roughly the same size, the object that looks the largest will be judged as being the closest to the observer.
* Absolute size, or the actual size of an object, also contributes to the perception of depth. Smaller objects, even if we don't know exactly how big they are, will look farther away than a large object placed in the same spot.
* Our familiarity with an object affects our perceptions of size and distance. While driving, your familiarity with the typical size of a car helps you determine how close or far away other vehicles on the road are from your location.
* An object position in relation to the horizon can also serve as a type of monocular cue. Objects located closer to the horizon tend to be perceived as farther away, while those that are farther from the horizon are usually seen as being closer.
* Another essential monocular cue is the use of texture to gauge depth and distance. When you're looking at an object that extends into the distance, such as a grassy field, the texture becomes less and less apparent the farther it goes into the distance.
* The perception of moving objects can also serve as a monocular cue for depth. As you're moving, objects that are closer seem to zoom by faster than do objects in the distance. 
* Objects that are farther away seem to be blurred or slightly hazy due to the atmosphere. As you look off into the horizon, closer objects seem more distinct while those in the distance might be obscured by dust, fog, or water vapor. Because objects in the distance tend to appear hazier, this cue tells us that blurry objects tend to be further away.
* Parallel lines appear to meet as they travel into the distance. For example, the outer edges of a road seem to grow closer and closer until they appear to meet. The closer together the two lines are, the greater the distance will seem.
* When one object overlaps another, the object that is partially obscured is perceived as being farther away. 
* The way light falls on objects and the amount of shading present can also be an important monocular cue. 
* In order to focus on close-up objects, certain muscles in your eye contract, altering the shape of your lens. When looking at objects that are far away, these same muscles relax. This accommodation can serve as a monocular cue, even though we are often unaware of it.
* All of these monocular cues contribute to our total experience of the scene, our perception of depth and distance, and our interpretation of our position in relation to other objects in the scene.

04/01/21
https://pypi.org/project/face-recognition/
* Find all the faces that appear in a picture:
* Get the locations and outlines of each person’s eyes, nose, mouth and chin.
* Recognize who appears in each photo.
* You can even use this library with other Python libraries to do real-time face recognition:
* pip3 install face_recognition
* When you install face_recognition, you get a simple command-line program
called face_recognition that you can use to recognize faces in a
photograph or folder full for photographs.
* If you are getting multiple matches for the same person, it might be that
the people in your photos look very similar and a lower tolerance value
is needed to make face comparisons more strict.
You can do that with the --tolerance parameter. The default tolerance
value is 0.6 and lower numbers make face comparisons more strict:
* There’s one line in the output for each face. The data is comma-separated
with the filename and the name of the person found.
An unknown_person is a face in the image that didn’t match anyone in
your folder of known people.
* If you simply want to know the names of the people in each photograph but don’t
care about file names, you could do this:
* https://github.com/ageitgey/face_recognition/blob/master/examples/web_service_example.py
* AWS Body post estimator: https://docs.aws.amazon.com/deeplens/latest/dg/deeplens-headpose-project-train-model-using-sagemaker.html
* https://aws.amazon.com/blogs/machine-learning/deploying-tensorflow-openpose-on-aws-inferentia-based-inf1-instances-for-significant-price-performance-improvements/
* 



03/31/21
TIL: https://towardsdatascience.com/5-awesome-computer-vision-project-ideas-with-python-machine-learning-and-deep-learning-721425fa7905
* https://www.upgrad.com/blog/computer-vision-project-ideas-for-beginners/
* https://pypi.org/project/face-recognition/
* Recognize and manipulate faces from Python or from the command line with
the world’s simplest face recognition library.
* Install on a raspberry pi: https://gist.github.com/ageitgey/1ac8dbe8572f3f533df6269dab35df65
* 
