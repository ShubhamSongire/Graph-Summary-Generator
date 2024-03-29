# Graph-Summary-Generator
A cutting-edge solution for summarizing graph images using deep learning, OCR, and image processing techniques. The system effectively classifies different types of graphs using a CNN model, and writes short summary about graph in a clear and concise paragraph-like format.

## Features
- Classifies different types of graphs using a CNN model
- Detects text within the images using AWS OCR
- Utilizes OpenCV and Numpy for accurate detection of the graph's axes and separation of the x-axis and y-axis labels
- Generates a comprehensive summary of the input graph's labels, title, and other important information in a clear and concise paragraph-like format
## Requirements
- Python 3.x
- TensorFlow
- OpenCV
- Numpy
- AWS OCR
## Installation
Clone this repository to your local machine and run the following commands to install the required packages:

``` shell
pip install tensorflow
pip install opencv-python
pip install numpy
pip install boto3
```
## Usage
Run the following command to start the Graph Summary Generator:

``` shell
python main.py
```

## Outputs
<div align="center">
    <a href="./">
        <img src="https://user-images.githubusercontent.com/68246393/215345546-9870dad3-ef5f-43f0-a0cc-12dcab63daed.jpg" width="59%"/>
    </a>
</div> <br>
<div align="center">
    <a href="./">
        <img src="https://user-images.githubusercontent.com/68246393/215345543-ba3cb93d-ac4c-4464-9bce-2ff156bbab3f.jpg" width="59%"/>
    </a> 
</div> <br>
<div align="center">
    <a href="./">
        <img src="https://user-images.githubusercontent.com/68246393/215346055-c1df6d12-8e4f-48c5-99c9-ca154a6a7f5d.jpg" width="59%"/>
    </a> 
</div> <br>
<div align="center">
    <a href="./">
        <img src="https://user-images.githubusercontent.com/68246393/215346231-5cd6781e-2cf9-4671-b9f2-b2213de9c1a8.jpg" width="59%"/>
    </a>
</div>

## Contributing
Contributions are welcome! If you would like to contribute to this project, please create a pull request.

## License
This project is licensed under the <a href="https://github.com/ShubhamSongire/Graph-to-Summary-Generator/blob/main/license.txt">License.</a>
