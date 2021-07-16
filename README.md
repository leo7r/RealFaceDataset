# RealFaceDataset

![cover](https://user-images.githubusercontent.com/6210797/126004776-48cf668a-e3f3-41d2-941b-51ad1f2540f2.jpg)


## Introduction
This repository contains a data collection of over 11000 pedestrian images taken in the wild. The data was collected from a variety of sources in the hope of creating a benchmark dataset for pedestrian face detection / recognition research.
The dataset contains over 55000 detected faces. The dataset is freely available for academic research purposes.

## Race Composition

Race | % of total faces
------------ | -------------
Asian | 13.43%
Black or African American | 5.22%
Hispanic or Latino | 5.97%
White | 75.37%

## Download

Download the Real Face sataset through [Google Drive](https://drive.google.com/file/d/1HoSQeLPCPZ9h1NkArCr2QsQhQ59p34TM/view?usp=sharing), unzip the downloaded file and you will get the following structure:

```
.
├── 1.jpg                   # Image file
├── 1.xml                   # Annotations file
├── ...
├── 11437.jpg
└── 11437.xml
```

## Annotation format

```
<annotation>
	<object>
		<name>face</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>773</xmin>
			<ymin>437</ymin>
			<xmax>796</xmax>
			<ymax>468</ymax>
		</bndbox>
	</object>
	...
</annotation>
```

## Contact

For questions and result submission, please contact Leonardo Ramos at 08-10921@usb.ve
