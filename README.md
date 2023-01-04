# IMT-Atlantique-2023
Graduate class content on ML for embedded systems

# Communication

[Webex/Zoom link](https://imt-atlantique.webex.com/meet/MSc-IT) -  https://imt-atlantique.webex.com/meet/MSc-IT

[Mattermost link](https://mattermost.imt-atlantique.fr/mooc-plido/channels/os-and-ml) - https://mattermost.imt-atlantique.fr/mooc-plido/channels/os-and-ml


#2023 Schedule

Jan 3rd, 13:45 - 15:00, 15:15 - 16:30

Jan 4th, 13:45 - 15:00, 15:15 - 16:30

Jan 10th, 13:45 - 15:00, 15:15 - 16:30

Jan 11th, 13:45 - 15:00, 15:15 - 16:30

Jan 18th, 13:45 - 15:00, 15:15 - 16:30

Note: TPIA on Jan 6th, Jan 13th (same time slots)

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

  


  
# Session 2 - Jan 4th

* I'll post the recording when it becomes available.

* [Machine Learning Frameworks](https://jhenry-github.github.io/Iot-ml-2022slides/slides_ml-iot2/#/2)
	* You will find many tools 'out there' that claim to support your ML work. Understanding the different types will help you choose wisely:
		* Some tools are open source ML frameworks. They include sets of commands and libraries that allow you to run most ML algorithms. The dominant players in this category include Scikit Learn (developed by an open source community), Tensorflow (developed by Google) and Pytorch (developed by Facebook/Meta). Be wary of 'science projects', frameworks that were developed in the past for a specific purpose, then stopped being maintained, surviving on their past fame.
		* Some tools are integrative frameworks. They are used in specialized tasks or fields where ML is a component. Examples include Matlab (widely used for mathematical modeling, for example in radio engineering) or R (widely used in statistical modeling and analysis). Most ML practitioners use these tools because they work in a field where these tools are common, not 'just' because of the ML support in these tools.
		* Some companies provide integrated environments, from where you can call most common frameworks, but also manage your data, your models, your connected objects, optimize your ML development tasks, access pre-computed models and more. Examples include Amazon SageMaker and IBM Watson Studio.
		* Some companies provide specialized ML development environments. For example, Edge Impulse specializes in ML optimizations for wearables and other constrained devices.
		* As you develop ML projects, you will need to make many attemps. Notebooks like Jupyter provide an easy way to document your attempts, with notes and segments of code that you can execute and which result / outcome you can visualize.
		* As you move beyond the research phase and work on deveopping full-blown ML solutions, IDEs like PyCharm provide powerful environments to develop and test/debug entire programs.
* [Supervised Learning](https://jhenry-github.github.io/Iot-ml-2022slides/slides_ml-iot2/#/18)
	* With Supervised Learning, you train a machine on a data set (the training set) to find the equation and parameters that best describes the data.
	* Your goal can be to find the equation that closely follows the data structure (linear regression). The machine then learns the parameters of a curve that is closest to the data points coordinates in your training set.
	* Your goal can be to organize data in two groups, and find to which group new data belongs. Logistic Regression is a tool of choice for this goal. LR is a powerful way of predicting the probability of an event, or of a group membership.
	* Your goal may be to find the boundaries between 2 or more groups. Support Vector Machines (SVM) are common tools for such goals, finding the equations (and parameters) of the boundary lines.
	* When working with decision trees, Random Forests provide an efficient way to predict an outcome, based on partial data.
	* Most supervised models can be made light enough to fit on edge devices like the ESP32. However, such compression comes with constraints. If the model is too big, it may run slower than the inference data pace. If the model is small but the underlying (training, inference) data too large, the inference or the trainig fail. Finding the right balance consume a good part of the ML development task.

* Session 2 exercises
	* Install Jupyter notebook or Studio. You can either downloand the [Standalone version](https://jupyter.org/install) or, better yet, install [Anaconda navigator](https://anaconda.org/anaconda/anaconda-navigator), for which Jupyter is one component that you can activate. 
	* Download the [data](https://github.com/jhenry-github/Iot-ml-2022slides/blob/main/Exercises/unconv_MV_v5.csv), the [exercise notebook](https://github.com/jhenry-github/Iot-ml-2022slides/blob/main/Exercises/Supervised_exercises.ipynb), open it in Jupyter, and follow the instructions. Of course, you can just use 'Shift enter' to run each line while thinking about something else. But then you just wasted your time and an opportunity to learn something fundamental to ML. So my suggestion is to read the code, for each line, and try to understand what the lines do. In an ideal world, you would also want to open a new Notebook, and paste one by one (or type from memory) the lines for the parts that interest you, put your own notes and keep these somehwere, as you will likley use the same type of structure millions of times as you work on new ML projects.
	* At the end of the course, you will need to send the exercise notebook (with all lines executed, and your answers to the questions in the notebook) to me.





# Session 3 - Jan 10th

* Possible solution to the exercises in session 2

* Unsupervised Learning

* Dimension Reduction

* Bayes
 
# Session 4 - Jan 11th

* Neural Networks

* ML on ESP-EYE

* Session 4 Exercise


# Session 5 - Jan 18th

* Review of ML on ESP EYE exercise

* Building a Succesful IoT ML Project





# Exercises
You will be asked to provide a report at the end of the course. It should contain your solution to the exercises, expressed in your own words. So, no cut and paste from the solution I provided and no 'joint homework'. The goal, for you, is to get familiar with the tools and the technology, and show that you are moving toward that familiarity. When a notebook is used for an exercise, you are expected to provide the notebook file, along with a document (which can be the markup section of the notebook, or a second document) showing how you worked through the problems, and what solution you found.



