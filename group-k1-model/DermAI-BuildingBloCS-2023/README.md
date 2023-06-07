# DermAI-BuildingBloCS-2023


Inspiration:
Skin cancer is a significant global health concern, and early detection plays a crucial role in improving patient outcomes. Traditional methods of diagnosing skin cancer often rely on visual examination by dermatologists, which can be subjective and prone to human error.

What it does:
Our AI model analyses skin samples and detects whether a skin-surface tumour present is benign or malignant

How we built it:
We found our data on Kaggle and made annotations to it on Roboflow. The data set was then exported into Yolov5 on Google Colab and the model was trained with 500 epochs. We then added Gradio for an interactive interface for users to upload photos into the model and check the tumours on their skin.

Challenges we ran into:
Being new to AI and machine learning, we were not sure where to start and which applications to use. However, with more in-depth research, we managed to proceed using the Yolo library. Additionally, we often faced errors in the code which we had to troubleshoot. Our AI model initially did not detect some skin samples and would detect random objects as benign or malignant. To prevent this from occurring again, we added pictures of the interiors of rooms to our dataset as null images.
 
Accomplishments that we're proud of:
We successfully managed to create a working AI model. We also were able to label our own dataset, train our model and create a user-friendly interface for uploading and processing content.

What we learned:
We have learnt how to train a model using Yolov5 and use Gradio as an interface for uploading and displaying the images, we have also learnt how to evaluate metrics to test the AI model.

What's next for DermAI:
We will try to add features such as the use of a webcam for greater convenience to users and to implement it as a web app or mobile app for greater accessibility and usability. We would also try implementing different augmentations, various training, validation and testing data ratios, and try creating a model with the newer Yolov8.
