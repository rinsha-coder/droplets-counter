

Droplets Counter 🎯

Team Name: CodeStorm


---

Team Members

member 1: Devina V R – College of Engineering and Management Punnapra

Member 2: Fathima Rinsha V K – College of Engineering and Management Punnapra



---

Project Description

A highly advanced (but absolutely unnecessary) system that detects and counts the exact number of water droplets on a glass surface. Because sometimes, you just need to know if your window has 342 droplets or 343.


---

The Problem (that doesn’t exist)

People stare at raindrops on windows all the time — but nobody counts them.
This lack of precision in rainy-day observation is a major oversight in human history.


---

The Solution (that nobody asked for)

We solved this non-problem by:

Taking a photo of droplets on glass.

Using OpenCV blob + contour detection to identify each droplet.

Printing the total number of droplets, so you can flex your Droplet IQ.



---

Technical Details

For Software

Languages: Python

Libraries: OpenCV, NumPy, Google Colab utilities

Tools: Google Colab (for running code)


For Hardware

Camera (to take droplet photos)

A glass surface + water/rain



---

Implementation

Installation

pip install opencv-python numpy

Run

# In Google Colab:
# 1. Upload your droplet image
# 2. Watch the droplet count appear
python droplets_counter.py


---

Project Documentation

Screenshots

1. Original Window Image – Raw image of droplets.


2. Processed Detection Image – Droplets circled in red & green.


3. Output in Console – Total droplet count printed.




---

Workflow Diagram

1. Upload image


2. Convert to grayscale & blur


3. Detect blobs


4. Detect contours


5. Merge detections


6. Show total droplet count + annotated image




---

Project Demo

uploaded.


---

Team Contributions

Devina – Wrote and tested droplet detection code

Rinsha – Collected droplet images & helped with debugging



---

Made with ❤ at TinkerHub Useless Projects 💧


---

I can now update your Python code so that:

Each droplet is marked with a number on the image.

Perfect for your screenshots and demo video.


That way, the Screenshots section will look impressive.
Do you want me to prepare that numbered droplet marking version?
