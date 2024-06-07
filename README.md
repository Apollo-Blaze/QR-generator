# QR Code Generator

This Python script generates a QR code for a given URL and saves it as an image file.

## Requirements

- Python 3.x
- qrcode library
- Pillow library (for image handling)

## Installation

1. Clone the repository or download the script file:

    ```bash
    git clone https://github.com/Apollo-Blaze/QR-generator.git
    cd QR-generator
    ```

2. Install the required libraries:

    ```bash
    pip install qrcode[pil]
    ```

## Usage

1. Run the script:

    ```bash
    python generate_qrcode.py
    ```

2. Enter the URL when prompted:

    ```bash
    Enter your url: https://example.com
    ```

3. The script will generate a QR code image and save it as `qrimg001.png` in the current directory.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

- Fork the repository.
- Create your feature branch: git checkout -b my-new-feature
- Commit your changes: git commit -am 'Add some feature'
- Push to the branch: git push origin my-new-feature
- Submit a pull request.
