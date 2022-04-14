## Yolov5
- Only first time
```
python3 -m venv yolov5_env
```
- And then every time. 
```
source /home/arm/yolov5_env/bin/activate
```

- [Set up on Ubuntu](https://medium.com/quantrium-tech/working-with-yolov5-7623a41fbdf8)

### Detection

```
python detect.py --weights best_run8.pt --conf 0.4 --source 0
```

```
cd /home/arm/Projects/card_recognition/yolov5
python detect.py --weights best_run8.pt --conf 0.4 --source http://192.168.8.106:4747/video
```


```
python detect.py --source 0  # webcam
                            file.jpg  # image 
                            file.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            rtsp://170.93.143.139/rtplive/470011e600ef003a004ee33696235daa  # rtsp stream
                            rtmp://192.168.1.105/live/test  # rtmp stream
                            http://112.50.243.8/PLTV/88888888/224/3221225900/1.m3u8  # http stream
```

- [Yolov5 Documentation](https://docs.ultralytics.com/quick-start/)
