# DeepLearning_Alphabet
Jaram DeepLearning Study - Recognition of Handwritten Alphabet.


## Getting Started
1. Clone this repository
```
cd workspace
git clone https://github.com/Jaram2019/DeepLearning_Alphabet
```

2. Activate python virtual environment
```
cd DeepLearning_Alphabet
sudo pip install virtualenv
virtualenv -p python3 .env  # Create a virtual environment (python3)
source .env/bin/activate  # Activate the virtual environment
```

3. Install requirements
```
pip install -r requirements.txt
```

4. Deactivate the virtual environment
```
deactivate  # Exit the virtual environment
```

## Requirements
```
virtualenv>=16.3.0
python>=3.6
pandas==0.23.4
numpy==1.15.1
pandas==0.23.4
numpy==1.15.1
matplotlib==2.2.3
tensorflow>=1.13.0rc (build for CPU-only)
tensorflow-gpu (build with GPU support)
```

## Project
[A-Z Handwritten Alphabets in .csv format](https://www.kaggle.com/sachinpatel21/az-handwritten-alphabets-in-csv-format)

#### Content
The dataset contains 26 folders (A-Z) containing handwritten images in size 28*28 pixels, each alphabet in the image is centre fitted to 20*20 pixel box.

Each image is stored as Gray-level

#### Acknowledgements
The images are taken from NIST(https://www.nist.gov/srd/nist-special-database-19) and NMIST large dataset and few other sources which were then formatted as mentioned above.
