py -3.8 -m venv yolov5_env
yolov5_env\Scripts\activate
python -m pip install --upgrade pip
python -m pip install ultralytics
python -m pip install -r requirements.txt
python detect.py --weights best_windows2.pt --source 0 --conf 0.25
