# MonetGAN: Monet-esque Masterpieces with CycleGAN

This project transforms ordinary photos into stunning paintings inspired by the style of Claude Monet, using a CycleGAN model. The model was developed using a dataset from the Kaggle competition [GAN Getting Started](https://www.kaggle.com/competitions/gan-getting-started), and the core of this repository lies in the ability to perform unpaired image-to-image translation.

## Project Overview

MonetGAN leverages CycleGAN, a generative adversarial network (GAN), to learn the mapping between two visual domains without paired examples. The model can transform photographs into art pieces that resemble Monet's iconic impressionist paintings. This approach makes it possible to apply the style of Monet to any photograph, producing visually compelling and artistic outputs.

While the core model has been developed, **the current implementation is still in Jupyter notebook format**, and deployment is a work in progress. Stay tuned for updates as the project evolves!

## Key Features

- **Unpaired Image Translation**: MonetGAN uses CycleGAN, enabling it to work without requiring paired images.
- **Claude Monet's Style Transfer**: The model captures the style of Claude Monet's masterpieces, applying it to everyday photos.
- **Notebook-Based Model**: The current model is fully implemented in a Jupyter notebook and can be easily run locally.
- **Upcoming Deployment**: The model will soon be deployed as a web app to make it more accessible for users to transform their photos into Monet-inspired paintings.

## Dataset

The dataset used in this project is sourced from the Kaggle competition [GAN Getting Started](https://www.kaggle.com/competitions/gan-getting-started), containing both Monet paintings and photos. The dataset allows the model to learn the artistic style of Monet and apply it to various images.

## Usage

Currently, the model can be run directly from the Jupyter notebook. Follow these steps to use the notebook:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/MonetGAN.git
    cd MonetGAN
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook:
    Open the `MonetGAN.ipynb` notebook in Jupyter and run through the cells to train the model and generate Monet-style artwork.

## Future Work

- **Model Deployment**: The model will be deployed as a web app using Flask or FastAPI, allowing users to upload their own photos and receive Monet-style paintings as output.
- **Improved Model Performance**: Further tuning of hyperparameters and model architecture to enhance the quality of generated images.
- **Interactive GUI**: Integrating a user-friendly interface for real-time image transformation.

## Contributing

Feel free to fork this repository, submit issues, or contribute by making pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
