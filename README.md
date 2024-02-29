# IMAGE COLORIZATION USING CONVOLUTIONAL NEURAL NETWORKS
**Image Colorization using Convolutional Neural Networks**

This project aims to automatically colorize black and white images using convolutional neural networks (CNNs), a deep learning technique in the field of computer vision. By leveraging the power of neural networks, this system can accurately predict and apply color information to grayscale images, thereby enhancing visual content and improving the aesthetics of the images.

**Features:**

- **Efficient Colorization:** The convolutional neural network architecture implemented in this project efficiently predicts the 'a' and 'b' color channels given the grayscale 'L' channel of an image, producing accurate colorization results.
  
- **Pre-trained Model:** The project utilizes a pre-trained CNN model, eliminating the need for extensive training on custom datasets. This allows for fast and efficient colorization of black and white images without requiring large computational resources.

- **Image Processing:** The colorization process involves various image processing techniques, including converting images to the LAB color space, combining color channels, and converting colorized LAB images back to the RGB color space for display.

**Usage:**

1. **Requirements:**
   - Python 3.x
   - OpenCV
   - NumPy

2. **Installation:**
   ```
   pip install opencv-python numpy
   ```

3. **Usage:**
   ```
   python colorization.py --image <path_to_input_image>
   ```

   Replace `<path_to_input_image>` with the path to the black and white image you want to colorize.

**Results:**

The colorization system produces visually appealing colorized images, enhancing the overall quality and aesthetic appeal of the input black and white images. The accuracy of colorization may vary depending on factors such as image complexity and lighting conditions.

**Contributing:**

Contributions to this project are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

**Acknowledgments:**

- This project was inspired by research in image colorization using convolutional neural networks.
- Special thanks to the contributors of OpenCV and NumPy libraries for their invaluable tools and resources used in this project.

**References:**

- Zhang, Richard, et al. "Colorful image colorization." ECCV 2016.
- Dahl, Ryan, et al. "Automatic colorization." ECCV 2016.
- Isola, Phillip, et al. "Image-to-image translation with conditional adversarial networks." CVPR 2017.
