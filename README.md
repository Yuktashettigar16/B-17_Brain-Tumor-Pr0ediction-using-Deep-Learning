# Project Name - Brain Tumor Prediction using Deep Learning

modelres50.h5 file is present in the link below

https://drive.google.com/file/d/1AJ97ea6BnOhPqwsaEmDNU-wVF4kYQBKQ/view?usp=sharing


## Environment Setup

### Prerequisites
- Python 3 or above
- pip package manager

### Installation Steps

1. Clone the project repository from GitHub:
   ```
   git clone https://github.com/Yuktashettigar16/B-17_Brain-Tumor-Pr0ediction-using-Deep-Learning.git
   ```

2. Navigate to the project directory:
  

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Download the pre-trained ResNet50 model:
   - Download the trained model (modelres50.h5 file) from this drive link: https://drive.google.com/file/d/1AJ97ea6BnOhPqwsaEmDNU-wVF4kYQBKQ/view?usp=sharing

5. Start the application:
   ```
   python app.py
   ```

6. Open your web browser and go to `http://localhost:8080` to access the application.


### Usage

1. Upload an image of a brain tumor through the web interface.
2. The application will process the image using the trained ResNet50 model.
3. The predicted tumor type (meningioma, pituitary, no tumor, or glioma) will be displayed on the screen.
4. The uploaded image and its corresponding prediction will be stored in the database for future reference.

### Contributing

Thank you for considering contributing to this project. If you have any suggestions, bug reports, or feature requests, please open an issue in the project repository. We welcome contributions from the community to improve and expand the capabilities of this brain tumor prediction system.


### Acknowledgments

- We would like to express our gratitude to the open-source community for providing the tools and libraries used in this project.
- Special thanks to the authors of the datasets used for training and evaluation.
