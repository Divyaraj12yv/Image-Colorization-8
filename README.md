# Task 8 :-
# Interactive User-Guided Colorization Description:


🧠 Key Features :-

User Input-Guided Colorization: Use "color points" (user-defined hints) to guide the model.

Interactive GUI:

Upload grayscale image

Select pixel/region with mouse click

Choose desired color via color picker

Dynamic Output: The model colorizes the image in real time based on updated user inputs.


✨ Techniques Used :-


Deep Learning Backbone: Modified U-Net or VGG-style encoder-decoder

User-Hint Input Format: Color points provided as additional input channels (e.g., as sparse matrices)

Color Propagation: Uses global and local hints to propagate color throughout the image

OpenCV + Tkinter / Streamlit: For interactive GUI


📷 Sample Workflow :-


Upload a grayscale image

Click on image points to assign colors

Preview the dynamically colorized result

Refine the color inputs for enhanced control

🙏 Acknowledgments:-

Based on ideas from Zhang et al. (2017) “Real-Time User-Guided Image Colorization with Learned Deep Priors”

Built with TensorFlow, OpenCV, and Streamlit
