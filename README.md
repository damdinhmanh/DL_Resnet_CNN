1. Train best.pt model by running:

2. Inference a image classify animal belong one of classes ["butterfly", "cat", "chicken", "cow", "dog", "elephant", "horse", "sheep", "spider", "squirrel"]:
   $python inference_image_cnn.py -p D:\AI_ML_DL\Deep_Learning_Project\DL_Resnet_Inference_Image\DL_Resnet_CNN\data\animals\test\cat\1.jpeg


3. Inference video write to each frame classify animal belong one of classes ["butterfly", "cat", "chicken", "cow", "dog", "elephant", "horse", "sheep", "spider", "squirrel"]:
  $python .\inference_video_cnn.py -p elephant.mp4
  -> write to ouput.mp4
