!pip install roboflow

from roboflow import Roboflow
rf = Roboflow(api_key="WPD2mQtSwYpm73poJHaa")
project = rf.workspace("project-goj3v").project("object-detection-plfgo")
dataset = project.version(1).download("yolov7")
