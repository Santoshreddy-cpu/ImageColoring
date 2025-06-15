# ImageColorizer

ImageColorizer is a tool for automatically colorizing black and white images using deep learning. This project uses a pre-trained model to add natural colors to grayscale photos, making them look more vivid and realistic.

## Features

- **Automatic colorization** of black and white images
- Utilizes state-of-the-art deep learning models
- Easy-to-use command line interface
- Supports common image formats (JPEG, PNG, etc.)

## Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/ayanbag/ImageColorizer.git
    cd ImageColorizer
    ```

2. **Create and activate a virtual environment** (recommended)

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To colorize a black-and-white image:

```bash
python colorize.py --input path/to/your/image.jpg --output path/to/save/colorized.jpg
```

**Parameters:**
- `--input`: Path to the input grayscale image.
- `--output`: Path where the colorized image will be saved.

Example:

```bash
python colorize.py --input images/grayscale_photo.jpg --output results/colorized_photo.jpg
```

## Demo

You can try the tool using the sample images provided in the `images` directory:

```bash
python colorize.py --input images/example_bw.jpg --output results/example_color.jpg
```

## Requirements

- Python 3.6+
- See `requirements.txt` for the full list of dependencies.

## Project Structure

```
ImageColorizer/
├── colorize.py
├── requirements.txt
├── README.md
├── images/
└── results/
```

## Contribution

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgements

- Pre-trained model and research inspiration from [Zhang et al., 2016](https://arxiv.org/abs/1603.08511)
- Thanks to the open-source community for supporting this project.
