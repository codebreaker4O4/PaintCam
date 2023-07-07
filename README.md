# Virtual Painting with Object Detection

This project enables you to create a virtual painting on the screen using object detection techniques with OpenCV. By detecting specific objects in the camera feed, you can use them as paintbrush tips to draw on the screen. The project utilizes masking to isolate colors, contour detection to build outlines of objects, and tracks the movement of the object to create dynamic brush strokes.

## Features

- Object detection and tracking using OpenCV.
- Real-time camera feed for interactive painting.
- Masking to isolate specific colors for painting.
- Contour detection to create brush outlines.
- Dynamic brush movement based on the object's motion.
- Support for a customizable array of BGR colors.

## Prerequisites

- Python 3.6 or higher
- OpenCV library
- PyCharm IDE (optional)

## Getting Started

### Setting up the Environment

1. Install Python 3.x from the official website: https://www.python.org/downloads/.
2. Install OpenCV library using the following command:

```shell
pip install opencv-python
```

3. Clone or download the project repository from GitHub.

### Running the Program

1. Open the project in your preferred Python development environment (e.g., PyCharm).
2. Run the `virtual_painting.py` script.
3. The camera feed will open, and you will be prompted to select the color range you want to use for painting.
4. Place an object with the desired color in front of the camera. The object will act as a paintbrush tip.
5. Move the object around, and you will see the painting being drawn on the screen based on the object's movement.

## Usage

1. Adjust the color range using the trackbars to isolate the desired color for painting.
2. Place an object of the selected color in front of the camera.
3. Move the object within the camera's field of view to create brush strokes on the screen.
4. Experiment with different colors and objects to create virtual paintings.


## Contributing

Contributions to this project are welcome! If you have any suggestions, bug reports, or improvements, please feel free to create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgments

- Thanks to the OpenCV community for providing the necessary tools and resources for computer vision applications.
- The contour detection and masking techniques used in this project were inspired by various OpenCV tutorials and examples available online.
