# Blind-Assistant-Bot
To create virtual environment :

pip install virtualenvwrapper-win
mkvirtualenv <name>
workon <name>
to run:

pip install -r requirements.txt
for installing torch_nightly: pip install "torch==1.8.*" --use-feature=2020-resolver --pre --extra-index-url https://download.pytorch.org/whl/nightly/cu102/torch_nightly.html
for installing torch_vision: pip3 install torch torchvision -f https://download.pytorch.org/whl/torch_stable.html
download yolov4.weights from here and put in root folder https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.weights
