# Facial-Recognition
This is python code for facial recognition from live feed using Haar Cascade and LBPH.

# About:
(The code was written using jupyter notebook)
- This is a simple menu based python code that detects faces using Haar Cascade and regocnises them using LBPH algorithm.
- Both Haar Cascade and LBPH are part of Open-CV lib.
- Lib used: Open-CV, Numpy, OS and Image from PIL.
- index.ipyb is the file that needs to be run.
- The recognition, training and detection code is given separately in the respective .ipyb files. (all 3 are part of index.ipyb)

# How to use:
- If you want a face recognised first register the face using the detect option (i.e option 1), which detects the face in from the video and saves it in the dataset folder with a id provided by you.
- If the face has been registered then you can use the recognise option (i.e option 2) to recognise the face from live video feed.
