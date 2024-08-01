# Virtual-Mouse
This project utilizes computer vision and hand tracking to control mouse using hand gestures. The implementation uses OpenCV for video capture, CVZone for hand detection, and PyAutoGUI for controlling the screen.

Features:
- **Mouse Control**: Move the mouse cursor with the index finger.
- **Mouse Clicks**: 
  - Left-click using index and middle fingers close together.
  - Right-click using index, middle, and ring fingers close together.
- **Double Click**: Double-click using only the index finger.
- **Mouse Scroll**: 
  - Scroll up using index, middle, and thumb fingers.
  - Scroll down using index, middle, thumb, and ring fingers.
 
Requirements:


1. Setting Up a Virtual Environment
Creating a virtual environment helps isolate your project and manage dependencies. Here's how to create and activate a virtual environment:

2.Create a virtual environment:
python -m venv venv

3.Activate the virtual environment:
Windows:
.\venv\Scripts\activate
Mac/Linux:
source venv/bin/activate

4. Installing Libraries
Once the virtual environment is activated, you can install the required libraries using pip.

Install OpenCV:
pip install opencv-python

Install CVZone:
pip install cvzone

Install Mouse:
pip install mouse

Install PyAutoGUI:
pip install pyautogui

Install NumPy (if not already installed):
pip install numpy

Applications:

The Virtual Mouse Using Hand Gestures project has several practical applications in the current scenario, especially given the increasing demand for touchless interfaces and innovative ways to interact with technology.

This project can be beneficial for individuals with physical disabilities who may have difficulty using traditional input devices like a mouse and keyboard. Hand gestures provide an alternative and potentially more accessible way to control a computer.

During presentations, speakers can use hand gestures to control slides, videos, and other media without needing to be near a computer. This allows for more dynamic and engaging presentations.

In remote work environments, this project can enhance virtual meetings by enabling touchless controls for screen sharing, adjusting volume, and navigating between applications, making meetings smoother and more efficient.

Hand gesture controls can be integrated into smart home systems, allowing users to control various devices (e.g., lights, thermostats, entertainment systems) with gestures, contributing to a more seamless and intuitive smart home experience.

In healthcare settings, touchless controls can be used in sterile environments where touching devices is not feasible. Surgeons and medical professionals can use gestures to navigate medical records, control imaging systems, and interact with other digital tools without compromising sterility.

In educational settings, teachers can use hand gestures to control digital blackboards, presentations, and other educational tools, allowing for more interactive and engaging lessons without being tied to a specific location in the classroom.

In industrial and manufacturing environments, touchless controls can improve safety and efficiency. Workers can operate machinery, control systems, and navigate interfaces without physical contact, reducing the risk of contamination and improving workflow.

This project can be extended to AR and VR environments, where hand gestures are a natural and intuitive way to interact with virtual objects and interfaces, enhancing user experience and immersion.
