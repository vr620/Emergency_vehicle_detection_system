# EMERGENCY_VEHICLE_DETECTION_SYSTEM

# ABOUT
Idea is to provide a tool to detect the emergency vehicles in the nearby path.

# IMPORTANT LIBRARIES
**1.pandas**

**2.Numpy**

**3.Tensorflow**

**4.matplotlib**

**5.librosa**

**6.sci-kit learn**

# ROADMAP

**1st approach**

1.From audio files we need to extract important features i.e. MFCCs, Spectral Centroid, Zero Crossing Rate, Chroma Frequencies, Spectral Roll-off.

2.Once the features have been extracted, they can be appended into a CSV file.

3.Various classification algorithms can be used to get better accuracy .

**some important feature are:



<img src="https://miro.medium.com/max/1400/0*QFVha2lCgyhKjhuO.gif"
     alt="https://miro.medium.com/max/1400/0*QFVha2lCgyhKjhuO.gif"
     style="float: left; margin-right: 10px;" />


**2nd approach**
1.We need to convert the audio files into PNG format images(spectrograms).

2.Train a CNN model for classification using these spectrogram images.

**some smaple pictures of spectrogram**

<img src="https://miro.medium.com/max/1000/1*jRw1HMPw0SpVffgZTVPT0g.png"
     alt="https://miro.medium.com/max/1000/1*jRw1HMPw0SpVffgZTVPT0g.png"
     style="float: left; margin-right: 10px;" />

# DATA

1.[link of data audio data](https://drive.google.com/drive/folders/1UjVKBwP0StsjvmfE4hohTnVpI8-Jmrmx)

2.[link of the image data](https://drive.google.com/drive/folders/1fZqHPQ0s43lS-ZIDekkabEEpy5lGON4w)

3.[link for the csv files](https://drive.google.com/drive/folders/1MbaZn5lAzVHRz7hB0G1KX77pDGIfBDEH)

# features_information

[feature_information](https://github.com/vr620/Emergency_vehicle_detection_system/blob/master/features_information.ipynb)

# Data preparation

1.[csv_preparation](https://github.com/vr620/Emergency_vehicle_detection_system/blob/master/csv_preparation.ipynb)

2.[img_data_preparation](https://github.com/vr620/Emergency_vehicle_detection_system/blob/master/spectrogram_extraction_preparation.ipynb)

# various algorithms

1.[ANN model](https://github.com/vr620/Emergency_vehicle_detection_system/blob/master/ANN_modal.ipynb)

2.[KNN model](https://github.com/vr620/Emergency_vehicle_detection_system/blob/master/KNN_way.ipynb)

