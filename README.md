# CS 370: Current and Emerging Trends in Computer Science

## Pirate Intelligent Agent — Deep Q-Learning

### Project Overview

For this project, I developed an intelligent pirate agent that uses deep Q-learning to navigate a maze and find treasure. The goal was to train the pirate to find the most effective path to the treasure while avoiding unnecessary movements and maximizing its rewards. This project demonstrated how reinforcement learning and neural networks can work together to solve pathfinding problems through experience and repeated training.

### What Code Was Provided, and What Did I Create?

The starter code provided the maze environment, movement options, reward system, experience replay functionality, and neural network model. It also included functions for testing the pirate's performance. My responsibility was to complete the Q-training algorithm that allowed the pirate to learn how to navigate the maze.

I implemented the training logic within the `qtrain()` function, allowing the agent to interact with the environment, collect experiences, and improve its decisions over multiple training episodes. The algorithm used exploration and exploitation to balance trying new actions with using previously learned information. I also tested the agent's performance to verify that it could consistently reach the treasure. By the end of training, the agent achieved a 100% win rate.

### What Do Computer Scientists Do, and Why Does It Matter?

Computer scientists use technology, algorithms, and problem-solving skills to develop solutions that make processes more efficient and effective. Their work includes designing software, analyzing data, improving security, and developing intelligent systems. This matters because technology plays an important role in nearly every industry, from healthcare and education to transportation and business.

Throughout this course, I learned how artificial intelligence can help computers recognize patterns, learn from experience, and make decisions. The pirate intelligent agent demonstrated how reinforcement learning can solve problems without requiring every decision to be programmed manually. These concepts can also be applied to real-world problems such as robotics, automated navigation, and resource optimization.

### How Do I Approach a Problem as a Computer Scientist?

I approach problems by first understanding the requirements and breaking the problem into smaller, manageable steps. From there, I determine which tools and algorithms are appropriate, implement a solution, and test it to identify errors or opportunities for improvement.

This project reinforced the importance of patience, experimentation, and troubleshooting. Developing the intelligent agent required understanding how rewards, actions, and training affected its performance. When something did not work as expected, I reviewed the code, examined the results, and made adjustments. I learned that problem-solving is often an iterative process and that testing is just as important as writing the code.

### What Are My Ethical Responsibilities to the End User and the Organization?

As a computer scientist, I have a responsibility to develop technology that is reliable, secure, fair, and transparent. Users should be able to trust that software works as intended and that their information is handled responsibly. Organizations also depend on developers to identify potential risks, protect sensitive information, and create systems that meet both technical requirements and ethical standards.

Artificial intelligence introduces additional responsibilities because intelligent systems can make decisions based on training data and reward structures. Poorly designed rewards or incomplete training data can lead to unexpected or harmful behavior. I believe it is important to test AI systems thoroughly, evaluate their limitations, and maintain human oversight when necessary. This course helped me understand that creating an effective solution is not just about whether the technology works, but also about how it affects the people who use it.

### AI Usage Acknowledgment

I used ChatGPT as a learning and troubleshooting resource while completing this project. It helped me better understand reinforcement learning concepts, review errors, and clarify parts of the implementation process. I worked through the project, tested the code, reviewed the results, and verified the final functionality. I also reviewed and edited this reflection to ensure it accurately represents my understanding and experience.
