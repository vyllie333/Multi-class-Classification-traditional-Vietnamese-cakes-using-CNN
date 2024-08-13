# Classify traditional Vietnamese-cakes using Convolutional Neural Network (CNN)

## Desciption
>#### The data collected by Huy Do (https://github.com/dobhuy) is then preprocessed and entered into the CNN model to train and evaluate the classification. 
> Huy Do has collected a dataset of images of various Vietnamese cakes, each meticulously labeled by type. Then, I preprocess these images to extract key features, such as texture, color, shape, and other distinctive visual attributes. Leveraging this data, I designed a convolutional neural network (CNN) model for multi-class classification. This model can analyze images of cakes uploaded by users and provide instant classification results, helping to promote and preserve Vietnam's rich culinary heritage.

## Authors
**Author**: Vy Vyllie

## Content
### Dataset

The dataset is organized as follows:
```text
Main-folder/
├── BanhVN
│   ├── BanhCay
│   │   ├── Banh_cay_1.jpg
│   │   ├── Banh_cay_10.png
│   │   ├── Banh_cay_100.png
│   │   ├── ...
│   │   ├── Banh_cay_139.png
│   │   ├── Banh_cay_14.png
│   │   ├── ...
│   │   ├── Banh_cay_9.png
│   ├── Banh_cay_bosung_1.png
│   ├── Banh_cay_bosung_10.png
│   ├── Banh_cay_bosung_11.png
│   ├── ...
│   └── Banh_cay_bosung_20.png
├── BanhChung
├── BanhGiayGio
├── BanhPia
├── BanhTaiHeo
├── BanhTieu
└── data_agumentation
    ├── BanhCay
    ├── BanhChung
    ├── BanhGiayGio
    ├── BanhPia
    ├── BanhTaiHeo
    └── BanhTieu
```

### Proprocessing: Use available package in cv2

### Classification using Convolutional Neural Network
* Model: 3 layers Conv, 1 layer FC, Output is multi class (5 labels) 
>  ![Image](https://github.com/vyllie333/Classify-traditional-Vietnamese-cakes-using-CNN/blob/main/modelcnn.jpg)
* Method
>  ![Image](https://github.com/vyllie333/Classify-traditional-Vietnamese-cakes-using-CNN/blob/main/method.jpg )
