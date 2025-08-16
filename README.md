# 🧙‍♂️ Harry Potter Invisibility Cloak (Python + OpenCV)

This project recreates the magic of Harry Potter’s invisibility cloak using computer vision! By detecting a specific cloak color in real-time video, the system replaces it with the background, making the person appear invisible. Built with Python, OpenCV, and NumPy, it’s a fun and interactive way to explore computer vision.

## 📌 Features
- Real-time color-based invisibility cloak effect
- Works with webcam or video input
- Morphological operations for smoother masking
- Easy to customize cloak color (default: red)
- Educational project for beginners in computer vision

## 🧠 Techniques Used
- **Background Capture**: Records the empty background before applying cloak effect  
- **Color Detection**: HSV color space thresholding to isolate the cloak color  
- **Masking**: Replace cloak regions with the background image  
- **Morphological Operations**: Noise removal and mask refinement  
- **Frame Blending**: Combine original frame and background for invisibility effect

## 📂 Project Structure
📁 InvisibilityCloak/
├── invisibility_cloak.py # Main script for cloak effect
├── demo.gif # Demo GIF or screenshot (add your own)
└── README.md # Project documentation

markdown
Copy
Edit

## 🚀 How to Run

1) **Install Dependencies**
```bash
pip install opencv-python numpy
Run the Application

bash
Copy
Edit
python invisibility_cloak.py
The Steps

Stand away from the camera for a few seconds while the background is captured.

Wave a red (or chosen color) cloak in front of the camera.

Watch yourself “disappear”!

Press q to quit.

🛠️ Customization
Modify HSV thresholds in invisibility_cloak.py to use a different cloak color.

Use a saved video instead of webcam by changing the video input source in the script.

Adjust morphological kernel size for more/less mask smoothing.

📽️ Demo Preview
<img src="demo.gif" alt="Invisibility Cloak Demo" width="500"/>
(Replace with your own GIF or embed a YouTube video link.)

👤 Author
Pavan Gembali — LinkedIn | GitHub

Enjoy becoming invisible with code! ✨
