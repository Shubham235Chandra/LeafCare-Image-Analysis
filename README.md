
# LeafCare Image Analysis

LeafCare Image Analysis is a Streamlit-based application wrapped in a Docker container designed to classify plant diseases from images. This application uses a pre-trained Convolutional Neural Network (CNN) to predict the type of disease affecting a plant based on its leaf image.

## Features

- **Image Upload**: Users can upload images of plant leaves to diagnose potential diseases.
- **Disease Prediction**: Utilizes a trained CNN model to classify diseases from images.
- **Interactive UI**: Built with Streamlit, offering an intuitive user interface for easy interaction.

## Interactive Web App

For an interactive experience, you can visit and use the web application hosted on Hugging Face Spaces at [LeafCare on Hugging Face Spaces](https://huggingface.co/spaces/Shubham235/LeafCare).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Docker installed on your machine to run the application in a container.

- [Install Docker](https://docs.docker.com/get-docker/)

### Installation

Clone the repository to your local machine:

```bash
git clone https://your-repository-url.git
cd into-the-project-directory
```

Build the Docker image:

```bash
docker build -t leafcare-image-analysis .
```

Run the Docker container:

```bash
docker run -p 8501:8501 leafcare-image-analysis
```

### Accessing the Application

Once the container is running, you can access the application by navigating to `http://localhost:8501` in your web browser.

## Built With

- [Python](https://www.python.org/) - The programming language used.
- [TensorFlow](https://www.tensorflow.org/) - The machine learning framework used.
- [Streamlit](https://streamlit.io/) - The web framework used.
- [Docker](https://www.docker.com/) - Containerization platform.

## Contributing

Please read [CONTRIBUTING.md](https://your-repository-url/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://your-repository-url/tags).

## Authors

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/Shubham235Chandra)

See also the list of [contributors](https://github.com/Shubham235Chandra/LeafCare-Image-Analysis) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Credits

- **Shubham Chandra** - *Project Lead and Developer*

## Dataset

This project uses the [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset) hosted on Kaggle, which contains images of plant leaves categorized by disease types.
