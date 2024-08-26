"# image-to-sketch" 
"# image-to-sketch" 

# Image to Pencil Sketch Converter Web Application

## Overview

The **Image to Pencil Sketch Converter** is a web application built using Flask and OpenCV that transforms images into pencil sketches. This tool provides users with a simple and intuitive interface to upload an image, convert it into a pencil sketch, and download the result. It also includes a feature to delete the image after it has been processed and downloaded.

## Features

- **Image Upload:** Users can upload images in various formats (e.g., JPEG, PNG).
- **Pencil Sketch Conversion:** Converts the uploaded image into a pencil sketch using advanced image processing techniques with OpenCV.
- **Download Option:** Users can download the pencil sketch after conversion.
- **Delete Option:** Allows users to delete the image after downloading the sketch to maintain privacy and manage storage.

## Installation

### Prerequisites

- Python 3.x
- Flask
- OpenCV

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kuldeepkd0603/image-to-sketch.git
   cd image-to-sketch
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask application:**
   ```bash
   python app.py
   ```

5. **Access the web application:**
   Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

1. **Upload Image:** Click on the "Upload Image" button and select an image file from your device.
2. **Convert to Sketch:** After uploading, click on the "Convert" button to generate the pencil sketch.
3. **Download Sketch:** Once the sketch is generated, a "Download" button will appear. Click it to download the sketch to your device.
4. **Delete Image:** If you wish to delete the image after downloading, click the "Delete" button.

## Project Structure

- **app.py:** The main Flask application file that handles routes and image processing logic.
- **templates/:** Contains the HTML files for the web interface.
- **static/:** Stores static files like CSS, JavaScript, and images.
- **uploads/:** Directory where uploaded images are temporarily stored (optional, can be handled dynamically).

## Future Enhancements

- **Multiple Image Formats:** Support for more image formats like GIF, BMP, etc.
- **Real-Time Preview:** Add a feature to preview the sketch in real-time before downloading.
- **Filter Options:** Implement additional filters and effects that users can apply to their sketches.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

## Contact

For any queries or feedback, please contact (mailto:your.kuldeepverma9755@gmail.com).

