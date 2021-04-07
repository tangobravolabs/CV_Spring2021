# CV_Spring2021

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
