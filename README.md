# IMT-Atlantique-2023
Graduate class content on ML for embedded systems

# Communication

Webex/Zoom link

Mattermost link


#2023 Schedule

Jan 3rd, 13:45 - 15:00, 15:15 - 16:30

Jan 4th, 13:45 - 15:00, 15:15 - 16:30

Jan 10th, 13:45 - 15:00, 15:15 - 16:30

Jan 11th, 13:45 - 15:00, 15:15 - 16:30

Jan 18th, 13:45 - 15:00, 15:15 - 16:30

Note: TPIA on Jan 6th, Jan 13th (same time slots)

# Exercises
You will be asked to provide a report at the end of the course. It should contain your solution to the exercises, expressed in your own words. So, no cut and paste from the solution I provided and no 'joint homework'. The goal, for you, is to get familiar with the tools and the technology, and show that you are moving toward that familiarity. When a notebook is used for an exercise, you are expected to provide the notebook file, along with a document (which can be the markup section of the notebook, or a second document) showing how you worked through the problems, and what solution you found.


# Session 1 - Jan 3rd

* [ML and embeded systems](https://jhenry-github.github.io/Iot-ml-2022slides/slides_ml-iot1/#/2)
	* IoT has become the main source of data for humans to understand the world
	* Traditional models collected data at the edge, then transported it to a central location where learning and inference would occur
	* A growing trend pushes processing toward the edge, where data is produced:
		* Some models train in the cloud, run inference at the edge
		* Some models also distribute learning at the edge
	* Design carefully, to balance computing efficiency, waste in data transport, training data / model / inference data size and architecture complexity
* [Machine learning principles](https://jhenry-github.github.io/Iot-ml-2022slides/slides_ml-iot1/#/23)
	* Machine learning is a subset of the Artificial Intelligence (AI) field
	* AI is a branch of computer science interested in having machines mimic the human brain (can be as simple as makinf if/then decisions)
	* ML covers AI operations where the machine the parameters of its tasks as it runs them
	* One noticeable early implementation is McCullogh and Pitts neuron in 1943 (binary 1/0 ouput based on sum of binary inputs)
	* Rosenblatt's Perceptron (1957) improves the model by allowing self-learning of the thresholds and rudimentary classification
	* The limitations of the Perceptron model contributed the a 'winter of ML' in the 1970s and 1980s
	* The need for statistical analysis and the apparition og GPUs brought ML back to the forefront of computer science in the 2000s
	* ML has become a very active field, which methods can roughly be categorized as Supervised Learning, Unsupervised Learning and Reinforcement Learning
	* Neural networks (aka Deep Learning) continue solving at scale problems where monolithic models plateau

  
