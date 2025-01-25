Gym Reps Tracker 🏋️‍♂️
A Gym Repetition Tracker powered by Machine Learning and Computer Vision, designed to help fitness enthusiasts track and analyze their workout repetitions efficiently and accurately

Features ✨
>Real-Time Tracking: Detect and count gym repetitions (e.g., squats, bicep curls, push-ups) using computer vision.
>Pose Estimation: Leverages advanced pose detection techniques for accurate movement analysis.
>User-Friendly Visualization: Displays visual feedback on tracked movements.
>Performance Insights: Provides data to monitor progress and maintain correct form.

How It Works 🚀
>Pose Detection: Uses Mediapipe's Pose Detection API to identify key body landmarks like elbows, wrists, and shoulders.
>Angle Calculations: Tracks joint angles in real-time to determine repetition patterns.
>Repetition Counting: Dynamically counts gym reps based on the user's movements.
>Feedback: Visual indicators guide users to improve workout form

Technologies Used 🛠️
>Python: Core programming language.
>Mediapipe: Pose estimation and keypoint detection.
>OpenCV: For video frame processing and rendering.
>Numpy: Used for angle calculations and array operations.

Installation ⚙️
1. Clone the repository:
   git clone https://github.com/nishantmishra2003/Gym-Reps-Tracker-git.git
   cd gym-reps-tracker
2. Create a virtual environment and activate it:
   python -m venv venv
   venv\Scripts\activate  # On Windows
   source venv/bin/activate  # On macOS/Linux
3. Install the required dependencies:
   pip install -r requirements.txt
4. Run the application:
   python gym_reps_tracker.py

Usage 🏃‍♀️
>Position yourself in front of a camera (e.g., a laptop webcam).
>Start the script and select the exercise type (e.g., squats, curls).
>Perform the exercise while the program tracks your repetitions in real-time.
>View the visual feedback and progress on the screen.

Future Enhancements 🔮
>Add support for multiple exercises with automatic detection.
>Incorporate AI models to analyze workout quality.
>Enable session saving and detailed analytics dashboards.
>Build a mobile app version for portability

Contributing 🤝
Contributions are welcome! If you'd like to improve the project, please fork the repository and create a pull request

Acknowledgments 💡
Thanks to the Mediapipe team for their incredible pose estimation library. Inspired by fitness enthusiasts who aim to combine tech and health

License 📜
This project is licensed under the MIT License. See the LICENSE file for details.
