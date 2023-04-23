# Yolov51.0_tensorrt
   修改了输入源为视频，可以直接调用摄像头识别。  
   推理代码仍然是wang-xinyu大佬的。  
   修改后代码在tensorrtx-yolov5-v1.0/yolov5/yolov5s.cpp中  

# 测试环境
   tensorrt 6.0.1.8  
   Ubuntu 18.04  
   cuda 10.2  
   cudnn 7.6  
   
 # 实测效果
   给定文件夹识别 速度从42ms提升到7ms  
   使用修改后的视频源识别，大概为166FPS  
   原来的de.py大概为120FPS  
