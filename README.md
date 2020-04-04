# AR-eyewear-master

AR-eyewear-master or NEUX it's a project that uses AI through OpenCV to break the barrier between the consumers buying glasses and the virtual stores giving them a way to try pairs of glasses on a web-based application using their webcams. 

Before developing this experiment the team did a mini round of interviews reaching about 50 different and unrelated persons and this was one of the most frequent problem among people that are looking to buy glasses online.

This demo runs on Python using the OpenCV library for Face Recognition using Haar-Cascades to track the faces and apply the filters.

Why Haar-Cascades?

In this stage we need something cheap and simple, OpenCV with this library the implementation is fast and we can break and fix the code without much problems, the documentation is pretty clear and there are a lot of projects around to get some inspiration. We don't want to waste code so using this simple traditional method to detect faces was one of the best choices.


Right now the app is running OK but with some major issues that needs to be solved.

1.- The model struggles to keep tracking the eyepairs when turning to the sides and this is a must. The model use is an Machine Learning aproach that works pretty good but maybe we could use a Deep Learning aproach.

2.- Wrap everything into a web-based app using a framework like Flask or Django

3.- Load more glasses models (Brands?)



# Files

click_and_change.py : function to click on window and change frames ( still not finished )

face.py : face detection using Haar-Cascades.

lens.py : virtual glasses try-on.

# Resources

1.- [Haar Cascades and Face Detection ](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_objdetect/py_face_detection/py_face_detection.html
)


