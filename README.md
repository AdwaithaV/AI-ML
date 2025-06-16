# 🎨 Color Detection Using OpenCV

This project allows users to detect colors in images or real-time webcam streams by clicking on a region of interest. On clicking a point in the image or frame, the application returns the **name** and **RGB values** of the closest matching color from a predefined dataset.

## 🚀 Project Goals

- Read input from an image or a live webcam stream.
- Detect mouse click events to select pixels.
- Extract and convert BGR to RGB values.
- Match the color to the closest predefined name using a color dataset.
- Display the detected color name and its RGB values on the image/frame.

---

## 🧠 Project Breakdown

### ✅ Stage 1: Read and Display an Image
- Load and show an image using OpenCV’s `cv2.imread()` and `cv2.imshow()`.

### ✅ Stage 2: Detect Mouse Clicks
- Use `cv2.setMouseCallback()` to detect mouse click events on the displayed image.

### ✅ Stage 3: Extract RGB Values
- On mouse click, capture BGR values from the clicked pixel.
- Convert BGR to RGB since OpenCV loads images in BGR format.

### ✅ Stage 4: Match Color to Known Names
- Use a `colors.csv` file containing color names and RGB values.
- Use **Sum of Absolute Differences (SAD)** to find the closest match between the clicked RGB and the dataset.

### ✅ Stage 5: Display Color Name and RGB Values
- Overlay a rectangle and text showing the color name and its RGB values on the image using `cv2.putText()` and `cv2.rectangle()`.

### 🔄 Stage 6 (Optional): Webcam Color Detection
- Replace image input with a webcam stream using `cv2.VideoCapture()`.
- Perform similar operations in real-time by continuously detecting the clicked pixel.

---

## 🧩 Modules Used

| Module   | Purpose                                  |
|----------|------------------------------------------|
| OpenCV (`cv2`) | Image processing, mouse interaction, webcam access |
| Pandas   | Reading and processing the `colors.csv` file |

---

## 📁 Dataset Used

**File**: `colors.csv`  
**Description**: Contains a list of color names and corresponding RGB values.

**Columns**:
- `color_name`
- `R`
- `G`
- `B`
- *(optional fields like hex code or index can be ignored if unused)*

---

## 🖥️ Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/color-detection-opencv.git
   cd color-detection-opencv
