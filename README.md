# Object-tracking
  * In this project i worked on deep sort tracking model with yolov3 [Pretrained weight] by using pytorch framework.

  * Object tracking says that first detect the object(object detection) then process into track an object.

  * Object tracking means capturing an image one by one frame.

  * Then,the system capture an first frame identify this is an person save it into an list or dict.

  * Then process next frame,the system identify ok this is a person were already present on a last frame.So system,

will skip it(Bounding box will tracking a image) and give a previous frame result and save it in list.

  * This process will continue.

# Steps
  * Download a yolov3 weights here: https://drive.google.com/file/d/13EVXixIlbKA-0TirhkFhnNbZlqTN50h-/view?usp=sharing

  * Download a coco dataset for identify an objects,person lot of https://github.com/karthick1845/Object-tracking/tree/main/detector/YOLOv3/cfg [availabel in my repo]

  * Then install requirements > pip install -r reqirements.txt.

  * Then open pytorch.org select older version of pytorch(1.4).

  * If you system will not a gpu then go to detector.py, Change Use_cuda=False

# USe cases

  In this project used in all kind of tracking models.
  
  *In some busy areas to identify speed of vehicles.
  
  *Social distance.
  
  *For security purpose.
