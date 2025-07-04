# Personalized-Adaptive-Learning-using-Q-Learning-for-Learners-with-Disabilities
This project demonstrates a simplified Q-learning-based adaptive system tailored to support learners with various disabilities. The goal is to recommend personalized learning strategies based on engagement levels and task performance, thereby enhancing accessibility and inclusiveness in digital learning environments.

# Key Features

Models learners with cognitive, visual, hearing, and motor impairments.

Considers both low and high engagement levels, as well as task completion speed.

Incorporates personalized learning strategies, including:

Text-to-Speech

Voice-Activated Navigation

Real-Time Captioning

Adaptive Pacing

Gamified Learning

Personalized Learning Pathways

Augmented Reality

Speech-to-Text

Implements a Q-table to represent state-action values.

Uses the epsilon-greedy policy to balance exploration and exploitation during learning.

# How It Works

States: Represent learner profiles based on disability type and engagement/task speed.

Actions: Represent adaptive learning strategies to be recommended.

Q-table: A table initialized with random values, updated through Q-learning.

Rewards: A predefined reward matrix that simulates the effectiveness of each action for a given learner profile.

Training Process: The agent simulates learning over 1000 episodes, selecting actions, receiving rewards, and updating its knowledge through the Q-learning algorithm.

# Sample Output (Illustrative)

lua
Copy
Edit
Learned Q-table:
[[...]]  # Final Q-values for each state-action pair

For state 'Visual Impairment - Low Engagement', the recommended action is 'Augmented Reality'.
Files Included

adaptive_learning_q_learning.py: Main Python script for the simulation.

README.docx: Project overview and usage guide (this file).

System Requirements

Python 3.x

# NumPy Library

To install dependencies:

bash
Copy
Edit
pip install numpy
Possible Future Enhancements

Integrate real-world user interaction data to refine the reward system.

Develop a user-friendly interface for interaction and recommendations.

Expand the state and action space to include more detailed learner profiles and strategies.

# Acknowledgments
This project was developed to support inclusive and intelligent learning environments using AI-based methods, particularly reinforcement learning, for learners with diverse accessibility needs.


