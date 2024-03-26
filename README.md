# Random-walk-mobility-model
This code simulates a random walk mobility model in a two-dimensional space.

Importing Libraries: The script imports necessary libraries, including numpy and matplotlib.pyplot.

Defining Parameters: Parameters such as the number of steps (num_steps), initial position (initial_position), and step size (step_size) are defined.

Initializing Position: The initial position is set to initial_position, and lists x and y are initialized to store the x and y coordinates of the position at each step.

Defining Directions: Four possible directions are defined as unit vectors: up, down, right, and left.

Simulating Random Walk: The code iterates through num_steps steps. At each step, a random direction is chosen using np.random.randint(0, 4), and the position is updated by adding the step size multiplied by the chosen direction vector. The x and y coordinates of the new position are appended to the x and y lists.

Plotting Results: The x and y coordinates are plotted using plt.plot() to visualize the random walk trajectory. The x-axis represents the x position, the y-axis represents the y position, and the title of the plot is set to 'Random Walk Mobility Model'.
