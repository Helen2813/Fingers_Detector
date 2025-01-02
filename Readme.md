# Hand Gesture Detection Project

This project is designed for detecting and analyzing hand gestures using computer vision techniques with OpenCV and scikit-learn. It processes a video feed, isolates hand regions, and detects the number of extended fingers using contour analysis and convex hulls.

---

## 🚀 **Features**

- **Background Subtraction:** Dynamic adaptation of the background using `cv2.accumulateWeighted`.
- **Region of Interest (ROI):** Focuses on a specific area of the video frame for hand detection.
- **Hand Segmentation:** Identifies the hand region using contour detection.
- **Finger Counting:** Utilizes convex hull and contour properties to count fingers.
- **Real-Time Processing:** Processes video frames in real-time.

---

## 📦 **Dependencies**

The project requires the following Python libraries:

- `opencv-python`
- `numpy`
- `scikit-learn`

To install dependencies, run:

```bash
pip install -r requirements.txt
```

## 🖥️ **Project Workflow**
1. Initialize the camera feed.
2. Adapt to the background using calc_accum_avg.
3. Identify the hand region using ROI segmentation.
4. Count fingers using count_fingers with contour analysis.
5. Display results in real-time with OpenCV visualization.