## Coin Detection

This experiment illustrates the process of detecting coins in an image using image processing techniques. The objective is to identify and count the number of coins present in the image.

### Process

1. **Image Loading**: The image containing the coins is loaded into the program.

2. **Preprocessing**: The image is converted to grayscale to simplify the detection process. This reduces the complexity by focusing on intensity rather than color.

3. **Gaussian Blur**: A Gaussian blur is applied to the grayscale image to reduce noise and smoothen the image, which helps in better edge detection.

4. **Edge Detection**: The Canny edge detector is used to find edges in the image. This step highlights the boundaries of the coins, making them easier to detect.

5. **Circle Detection**: The Hough Circle Transform is employed to detect circles in the image. This algorithm identifies circular shapes based on the detected edges.

6. **Visualization**: Detected circles (coins) are drawn on the image to visualize the results. Each detected coin is marked, and the total count of coins is displayed.

By using these techniques, the experiment successfully identifies and counts the coins in the image, showcasing the effectiveness of image processing for object detection tasks.
