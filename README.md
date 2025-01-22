# Car and Bus Detection using Faster R-CNN and YOLO v11 🚗🚌  

This repository showcases a project for detecting cars and buses using **Faster R-CNN** and **YOLO v11**.  

## 🗂️ Data Source  
We used the **Open Images V7** dataset as our primary data source. The images were annotated using **Roboflow**, which generated three folders:  
- **Train**  
- **Validation**  
- **Test**  

Each folder contains:  
- **Images** (`.jpg`, `.png`)  
- **Annotations** in YOLO-compatible `.txt` format  

---

## 🚀 Workflow  

1. **Dataset Preparation**  
   - Images were uploaded to **Roboflow** for annotation using bounding boxes.  
   - Roboflow exported the data into Train, Validation, and Test folders.  

2. **Model Selection**  
   - **Faster R-CNN**: For a balance between accuracy and speed.  
   - **YOLO v11**: For real-time object detection.  

3. **Training and Evaluation**  
   - Models were trained on the **Train** dataset.  
   - Performance was validated on the **Validation** dataset.  
   - Final evaluation was conducted using the **Test** dataset.  

---

## 📁 Folder Structure  

Here’s the dataset structure:  

```plaintext
📦 Dataset
 ┣ 📂 Train
 ┃ ┣ 📂 images
 ┃ ┣ 📂Label
 ┃ ┣ ...
 ┣ 📂 Validation
 ┃ ┣ 📂 images
 ┃ ┣ 📂Label
 ┣ 📂 Test
 ┃ ┣ 📂 images
 ┃ ┣ 📂Label


## Results
the results of using faster r-cnn are not very good because the unbalanced labels for the buss class are very few. so that the accuracy metrics obtained are as follows
![Matrix Accuracy](Matrix%20Acuration.jpeg)  

![image](https://github.com/user-attachments/assets/117436c4-36ab-462f-a076-59c0e3cf2d31)


