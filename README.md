🧭 1D Random Walk Simulator

A simple Python simulation that visualizes a 1-dimensional random walk using NumPy and Matplotlib.
This project demonstrates how random movements can accumulate over time to form a random path.

📘 Description

The 1D Random Walk Simulator generates a sequence of random steps, either forward (+1) or backward (–1), and tracks the position after each step.
The resulting plot shows how the position evolves as the number of steps increases.

🚀 Features

Simulates random walk with any number of steps

Visualizes movement over time using Matplotlib

Demonstrates concepts of probability and randomness

🧩 Requirements

Make sure you have the following Python libraries installed:

pip install numpy matplotlib

🧠 How It Works

Each step is randomly chosen as +1 or –1 using np.random.choice.

The cumulative sum of all steps gives the position over time.

The path is plotted using Matplotlib.
