# Live-Face-Recognition
![alt text](https://github.com/akhil-sodari/Live-Face-Recognition/blob/master/demo.jpg?raw=true)

## Description
This project helps to recognise faces which are trained to the classifier using Local Binary Patterns Histograms((LBPH). Although there are more efficient ways to
perform Face Recognition like Deep Learning, this project just  uses a basic model which is good to know at beginner level.

## Steps

### Step 1 - Create Training Data
First and foremost we will prepare the data. So you need to capture atleast 100photos of your face, and store them in the folder \faces\users. However the code in the first cell
does that thing for you.

### Step 2 - Train Model
Here we will train our model using the dataset created in step-1.

### Step 3 - Run the model
We will just run the model created in step-2.

## Installation
You can install Anaconda to get all the required modules for this project or install the below modules on to you host using pip.

* NumPy
```bash
pip install numpy
```
* OpenCv
```bash
pip install opencv
```

You can find the Classifier in the folder named "Haarcascades"

## Clone the project
```bash
git clone https://github.com/akhil-sodari/Live-Face-Recognition.git
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)






