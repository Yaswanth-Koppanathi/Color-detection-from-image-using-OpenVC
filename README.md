# Color Detection from Image

This project is a simple **Color Detection System** using OpenCV and Python. It allows users to click on an image and detect the closest color name based on an existing dataset.

## Features 🚀

- Detects colors from an image when clicked.
- Displays the **color name** and **RGB values** in a colored rectangle.
- Uses a **predefined CSV dataset** to match the closest color.
- Interactive GUI using **OpenCV**.

## Installation 🛠️

To run this project, ensure you have **Python 3.x** installed along with the required dependencies.

### Install Required Libraries

```sh
pip install opencv-python pandas
```

## Usage 🎨

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/color-detection.git
   cd color-detection
   ```
2. Place your image in the project folder.
3. Run the script:
   ```sh
   python color_detection.py
   ```
4. **Double-click on any point in the image** to detect its color.

## Project Structure 📂

```
color-detection/
│── colors.csv                 # CSV file containing color names and RGB values
│── color_detection.py          # Main Python script
│── image.jpg                   # Sample image for testing
│── README.md                   # Project documentation
```

## How It Works ⚙️

1. The script loads an image using OpenCV.
2. It listens for **mouse double-click events**.
3. When clicked, it extracts the **RGB color values** at that point.
4. The script compares these values with a **color dataset (CSV file)** to find the closest matching color.
5. The detected color name is displayed in a rectangle at the top of the image.

## Example Output 🖼️

When clicking on a **red area**, the output might look like this:

```
Color Detected: Red (255, 0, 0)
```

## Contributing 🤝

Feel free to **fork this repository** and submit pull requests for improvements!

## License 📜

This project is licensed under the **MIT License**.

---

🔗 **Follow me on GitHub:** https://github.com/Yaswanth-Koppanathi


