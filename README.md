# Kids-Learning-App
Project Overview
This interactive learning application is designed to engage kids in a fun and educational way through voice recognition and interactive feedback. The app combines the power of speech recognition and machine learning to teach children about numbers, motions, and animals. With an intuitive interface, kids can actively participate by speaking their responses and receive real-time feedback for their efforts. The app includes gamified elements such as moving characters and changing images to keep the experience exciting and motivating.

Features
Voice-Activated Learning Modules:

Three main modules: Learn Numbers, Learn Motions, and Learn Animals.
Kids can interact with the app by speaking the answers, which are recognized using pre-trained machine learning models.
Dynamic Feedback System:

Provides immediate feedback within the same frame, displaying "Correct!" in green or "Wrong, try again!" in red.
Updates the content dynamically when the child gives the correct response.
Interactive Animations:

In the "Learn Motions" module, kids can direct a moving character (Dora) within a box by saying commands like "Up," "Down," "Left," or "Right."
Kid-Friendly Interface:

Clean and vibrant design with a background image and colorful buttons.
Easy-to-read text and a clear layout.
Gamified Elements:

Images for numbers and animals change dynamically upon correct responses to maintain engagement.
Real-time character movements based on voice commands in the motion learning module.
Technology Stack
Programming Language: Python
GUI Framework: Tkinter
Speech Processing:
SoundDevice: For audio recording.
Librosa: For feature extraction (MFCC).
Machine Learning Models: TensorFlow/Keras.
Image Processing: PIL (Pillow) for managing images and resizing.
Real-Time Feedback: Tkinter widgets for immediate user response.
How It Works
Learn Numbers:

The app displays a number image and prompts the child to say it.
If the child’s response matches the displayed number, they are shown a "Correct!" message, and the number changes.
If incorrect, they are encouraged to try again.
Learn Motions:

Kids give commands like "Up," "Down," "Left," or "Right" to move a character (Dora) within a box.
Each correct command is executed with visual feedback and a message.
Learn Animals:

The app displays an animal image, and the child is asked to name it.
Correct responses lead to the next animal image, while incorrect responses prompt them to try again.
