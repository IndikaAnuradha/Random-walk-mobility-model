# Random-walk-mobility-model
The mobility model is designed to describe the movement pattern of mobile users, and how their location, velocity and acceleration change over time.
In random-based mobility models, the mobile nodes move randomly and freely without restrictions.

This code simulates a random walk mobility model in a two-dimensional space.

Importing Libraries: The script imports necessary libraries, including numpy and matplotlib.pyplot.

Defining Parameters: Parameters such as the number of steps (num_steps), initial position (initial_position), and step size (step_size) are defined.

Initializing Position: The initial position is set to initial_position, and lists x and y are initialized to store the x and y coordinates of the position at each step.

Defining Directions: Four possible directions are defined as unit vectors: up, down, right, and left.

Simulating Random Walk: The code iterates through num_steps steps. At each step, a random direction is chosen using np.random.randint(0, 4), and the position is updated by adding the step size multiplied by the chosen direction vector. The x and y coordinates of the new position are appended to the x and y lists.

Plotting Results: The x and y coordinates are plotted using plt.plot() to visualize the random walk trajectory. The x-axis represents the x position, the y-axis represents the y position, and the title of the plot is set to 'Random Walk Mobility Model'.

![RWMB](https://github.com/IndikaAnuradha/Random-walk-mobility-model/assets/122884553/e2351f00-b48f-47c7-917e-3c05afc8e35e)

To learn more about the topic refer below links....

https://link.springer.com/content/pdf/10.1007/978-1-4419-6050-4_3.pdf

https://www.cise.ufl.edu/~helmy/papers/Survey-Mobility-Chapter-1.pdf

https://zenhadi.lecturer.pens.ac.id/kuliah/ns3/Teori/4%20Mobility%20model.pdf

![Visitor Badge](https://visitor-badge.glitch.me/badge?page_id=IndikaAnuradha.Random-walk-mobility-model)

