# Parrot 🦜 or Forest 🌲🌳 Image Classifier

## Overview

This project is developed as part of the "Practical Deep Learning for Coders 2022" course by Jeremy Howard, aimed at showcasing the practical application of deep learning techniques in image classification. Leveraging the DuckDuckGo search engine, the project sources approximately 300 images each of parrots and forests. These images are then used to train a ResNet18 model to accurately classify images into one of the two categories: parrot or forest.

## Course Context

This repository contains work completed as part of the "Practical Deep Learning for Coders 2022" course offered by FastAI and taught by Jeremy Howard. The course emphasizes hands-on learning with deep learning technologies, focusing on real-world applications. This project specifically applies course concepts to distinguish between images of parrots and forests using a trained neural network.

## Project Files

For convenience, this repository includes both a Jupyter Notebook (`*.ipynb`) file, which provides an interactive environment for exploring the project's code and methodology, and a Python (`*.py`) file for those who prefer a straightforward script format.

## Methodology

### Image Collection

- **Search and Download:** Utilizing the DuckDuckGo search API, the project fetches around 600 images in total, evenly split between images of parrots and forests.

### Data Preparation

- **Duplicate Removal:** A hash-based approach is employed to identify and remove any duplicate images, ensuring the dataset's integrity and uniqueness.

### Model Training

- **ResNet18:** This model is chosen for its effectiveness and efficiency in image classification tasks. The project uses this pre-trained model and fine-tunes it with our specific dataset.

### Prediction and Evaluation

- **Testing:** The trained model is then tested on new images to evaluate its accuracy and reliability in classifying them as either a parrot or a forest.

## Implementation Details

Implemented in Python, this project leverages the FastAI library for building and training the deep learning model. The FastAI library simplifies many of the complex aspects of training deep learning models, making it accessible to coders of various skill levels.

### Key Libraries and Tools

- **FastAI:** Facilitates the training and evaluation of deep learning models.
- **DuckDuckGo Search API:** Used for automating the search and download of images.
- **Python Imaging Library (PIL):** Supports image processing tasks necessary for preparing the training dataset.

## Conclusion

By employing deep learning techniques and the ResNet18 model, this project successfully demonstrates the capability to classify images into distinct natural categories with high accuracy. It showcases the potential applications of machine learning in recognizing and differentiating between complex visual patterns in nature.

## Future Work

To further improve the model's performance, future iterations of this project could include expanding the dataset, experimenting with more advanced models, and refining the training process for even greater accuracy and efficiency.

## Acknowledgments

This project was created as part of the "Practical Deep Learning for Coders 2022" course by Jeremy Howard, offered through FastAI. The course's hands-on approach and emphasis on practical application in the field of deep learning have been instrumental in the completion of this project.

## Image Usage Disclaimer

The images used in this project for training the model were sourced from the web via the DuckDuckGo search engine as part of an educational exercise. It is important to note that these images are provided as examples for personal and educational use only and may not be used for commercial purposes. Each image retains its original rights, and the use of these images is individual and non-transferable. No license for free or commercial use of the images is provided or implied.

Users of this project should ensure they comply with all applicable laws and copyright agreements when sourcing images for their own use. This project and its maintainers do not assume responsibility for any copyright infringement or legal issues resulting from the use or misuse of the images.

## Commercial Use Disclaimer

This project, including the final model, code, and documentation, is licensed under the Apache-2.0 License, allowing for both personal and commercial use. However, users intending to utilize the model for commercial purposes are required to ensure that all images or data used with the model are appropriately licensed for such use.

The images sourced from the web via the DuckDuckGo search engine for training purposes are provided as examples for educational and personal use only. Users are responsible for obtaining the necessary rights and licenses for any images or data used in a commercial setting.

By using this model, you acknowledge and agree to comply with all relevant copyright laws and licensing agreements. The responsibility for ensuring that any commercial application of the model is legally compliant rests solely with the user.

## Licensing

This project is licensed under the Apache-2.0 License, which permits unrestricted use, distribution, and modification, including commercial applications, provided that all conditions of the license are met. Users are encouraged to review the license terms carefully to ensure compliance with its conditions.
