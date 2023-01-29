# Graph-to-Summary-Generator
A cutting-edge solution for summarizing graph images using deep learning, OCR, and image processing techniques. The system effectively classifies different types of graphs using a CNN model, and writes short summary about graph in a clear and concise paragraph-like format.

## Features
Classifies different types of graphs using a CNN model
Detects text within the images using AWS OCR
Utilizes OpenCV and Numpy for accurate detection of the graph's axes and separation of the x-axis and y-axis labels
Generates a comprehensive summary of the input graph's labels, title, and other important information in a clear and concise paragraph-like format
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
## Contributing
Contributions are welcome! If you would like to contribute to this project, please create a pull request.

## License
This project is licensed under the <a href="https://github.com/ShubhamSongire/Graph-to-Summary-Generator/blob/main/license.txt">MIT License.</a>
