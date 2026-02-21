# gem-visualizing
A small project to easily visualize gem size in ratio to finger

First I use "The MediaPipe Hand Landmarker task" to detect the finger. 

<img width="337" height="352" alt="Hand_landMark" src="https://github.com/user-attachments/assets/a3fde83a-767c-4cff-a70d-602638cfc308" />

After that, extracting value from _detection_result.hand_landmarks_ to calculating length of finger to calculate ratio later.

<img width="310" height="330" alt="Finger_ring_landMark" src="https://github.com/user-attachments/assets/ababedb4-faf9-431a-8a8e-937e07db21e3" />

Read the gemstone image, resize with the ratio pixel to mm has been calculated before. After that, remove back ground of it. 

<img width="457" height="451" alt="Gemstone_removeBG" src="https://github.com/user-attachments/assets/e15612a8-5570-4d67-a047-2134b5d9db11" />

Finally, put the gemstone image on top of the hand image. In this case I use 1 carat heart shape gemstone ~ 6mm.

<img width="337" height="382" alt="Final_result" src="https://github.com/user-attachments/assets/6a1a047c-ca3c-4e16-837e-16c0f0121cef" />
