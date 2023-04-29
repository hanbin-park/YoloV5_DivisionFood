# YoloV5_DivisionFood


RES_DIR = set_res_dir()
if TRAIN:
    !python train.py --data ../data.yaml --weights yolov5s.pt \
    --img 640 --epochs {EPOCHS} --batch-size 16 --name {RES_DIR}
    
    
Result

![image](https://user-images.githubusercontent.com/83060689/235306488-02ab91a9-2a2e-4cb9-9dbb-051eca0fd287.png)
