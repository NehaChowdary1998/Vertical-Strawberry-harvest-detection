# Project Title 
Autonomous Robotic Harvesting of Strawberry in Vertical Growing System 

## Overview
Developed a novel deep-learning-based vision system to detect and localise complex, occluded strawberry clusters in real  time, supporting autonomous robotic harvesting by integrating state-of-the-art perception, manipulation, and control modules  to enable efficient, damage-free fruit collection. 

<img width="479" height="282" alt="thumbnail_image001" src="https://github.com/user-attachments/assets/decc302f-7470-4a3e-ad00-1fa06a80b25c" />

## Dataset
Atleast 300 Strawberry cluster images were collected from Tiptree farm UK. 

<img width="1168" height="657" alt="thumbnail_image005" src="https://github.com/user-attachments/assets/23ff46a0-e143-45c3-9768-3e8adbdd7e0d" />

## Approach
- The data collected from the farm was annotated using Roboflow Segmentation method (refer to the uploaded file --> Strawberry data training git.mp4)
- The strawberries were classified into 3 difficulty levels(easy, moderate, hard) and direction( left, right, human).
- The novel approach used to get the desired output is to annotate the stem of the strawberry to train the model to identify the stem associated with the strawberry.
- The annotated images were split into train 70%, Validation 20%, and test 10% to ensure a balanced distribution of images across all categories.
- The model was trained using YoloV11. Results included in the end --> https://github.com/user-attachments/assets/bc286296-89bc-4c02-9ea2-e73c4947915f  

## Tools & Technologies
Roboflow segment annotation, Python, TensorFlow, PyTorch, YOLOv11, ROS( Robot Operating System)

## Results
- The final results of the trained model.

<img width="1812" height="1019" alt="image" src="https://github.com/user-attachments/assets/2343633e-b211-4e4b-9097-49ca25c6e2ec" />

- The Final demonstration was done using the Robot, replicating the farm environment with the strawberries.
  please refer to the video attached - https://github.com/user-attachments/assets/9afbc7b0-245f-47eb-beaf-da8b33bbadd4

- Business impact metrics
• Implemented stem classification techniques that enhanced cutting precision by 50% in manufacturing processes.  
• Recommended efficient approach trajectories and difficulty levels, improving berry occlusion access by 70% using Roboflow's 
segmentation technique.  
• Developed and optimized YOLOv11 Segmentation model, achieving 85% accuracy in real-time detection of ripe strawberries 
across diverse canopy structures.  
• Experimented on vertical farming systems at Wilkins and Son's Tiptree farms, UK, achieving 75% accuracy in crop yield 
predictions.  

## Future Improvements
Scaling ideas
- As data collection and annotation is a tiring process a simple yet efficient approach is to use blender to create the farm environment with clusted strawberries and using in built blender cameras to capture images and collaborate/connect to python to store and automate annotating the images and train the model.

## Author
www.linkedin.com/in/nehachowdaryb, chowdaryneha1998@gmail.com
