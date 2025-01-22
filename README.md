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

The dataset is organized into the following structure:  

- **Train**  
  - `images/` - Contains all training images.  
  - `labels/` - Contains annotation files in YOLO format.  
- **Validation**  
  - `images/` - Contains all validation images.  
  - `labels/` - Contains annotation files in YOLO format.  
- **Test**  
  - `images/` - Contains all test images.  
  - `labels/` - Contains annotation files in YOLO format.  

---

## 📈 faster R-CNN Results  

The results of using Faster R-CNN are not very good due to unbalanced labels, especially for the bus class. The accuracy metrics obtained are as follows:  

### Matrix Evaluation  
![Matrix Accuracy](https://github.com/user-attachments/assets/831f5fb4-076a-4c5a-b304-32d0cb1fb1d2)  

### Test 
Below is the results

![Test on 1 image](https://github.com/user-attachments/assets/117436c4-36ab-462f-a076-59c0e3cf2d31)  

---

## 📈 YOLO V11 Results  

### Test
Below is a results

![Test on 1 image](https://github.com/user-attachments/assets/ea42caf9-acf7-46b1-a44c-e68db79c268c)
)  


Feel free to contribute or report any issues in this project! 🚀  
