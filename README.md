# Animal-Intrusion-Detection
> Animal Intrusion Detection using yolov5

### Preparing the Data
- Various classes are collected (Tiger, Giraffe, Lion, Monkey, Cow ...)
- The collected data was labelled

### Spliting the Data
- The data is split into train and validation which is of the ratio 80:20
- The prepared dataset is uploaded into the drive

### Cloning of Yolov5 and installing requirements
- The yolov5 github repo was cloned into google colab
- The data is mounted onto the google drive
- The dataset is unzipped for further accessing
- All the requirements for yolov5 are installed

### Data training and Validation
- Mark the given config files as required
- the training of model is done with image size 415, batch size - 31, epochs -100
- Weights of yolov5s is given
### Inference
- The inference files are uploaded (video, images)
- The inference with the weights of best.pt is done
### Display
- The detected image is displayed

### Predictions
> Image
<p align="center" width="100%">
    <img width="80%" height="450" src="https://github.com/SaiSwarup27/Animal-Intrusion-Detection/blob/main/Images/pred_cattle.jpg">
</p>

> Video </br>

https://user-images.githubusercontent.com/96674419/171603746-b8281df0-1d90-4378-9830-50f71404b53d.mp4




