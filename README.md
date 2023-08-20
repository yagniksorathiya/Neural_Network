# Neural_Network

## Problem Statement

**Fireforest :**

Predict the burned area of Forest fires with Neural Networks

**Gas Turbine :**

Predicting turbine energy yield (TEY) using ambient variables as features.

# ➳ Neural Network

![Neural network](https://github.com/yagniksorathiya/Neural_Network/assets/129974278/2a41deba-d949-443a-8a62-67324a339c16)

## ↳ What is a neural network?

A neural network is a method in artificial intelligence that teaches computers to process data in a way that is inspired by the human brain. It is a type of machine learning process, called deep learning, that uses interconnected nodes or neurons in a layered structure that resembles the human brain. It creates an adaptive system that computers use to learn from their mistakes and improve continuously. Thus, artificial neural networks attempt to solve complicated problems, like summarizing documents or recognizing faces, with greater accuracy.

## ↳ Why are neural networks important?

Neural networks can help computers make intelligent decisions with limited human assistance. This is because they can learn and model the relationships between input and output data that are nonlinear and complex. For instance, they can do the following tasks.

**Make generalizations and inferences**

Neural networks can comprehend unstructured data and make general observations without explicit training. For instance, they can recognize that two different input sentences have a similar meaning:

+ Can you tell me how to make the payment?

+ How do I transfer money?

A neural network would know that both sentences mean the same thing. Or it would be able to broadly recognize that Baxter Road is a place, but Baxter Smith is a person’s name.

## ↳ What are neural networks used for?

Neural networks have several use cases across many industries, such as the following:

+ Medical diagnosis by medical image classification

+ Targeted marketing by social network filtering and behavioral data analysis

+ Financial predictions by processing historical data of financial instruments

+ Electrical load and energy demand forecasting

+ Process and quality control

+ Chemical compound identification

We give four of the important applications of neural networks below.

**Computer vision**

Computer vision is the ability of computers to extract information and insights from images and videos. With neural networks, computers can distinguish and recognize images similar to humans. Computer vision has several applications, such as the following:

+ Visual recognition in self-driving cars so they can recognize road signs and other road users

+ Content moderation to automatically remove unsafe or inappropriate content from image and video archives

+ Facial recognition to identify faces and recognize attributes like open eyes, glasses, and facial hair

+ Image labeling to identify brand logos, clothing, safety gear, and other image details

**Speech recognition**

Neural networks can analyze human speech despite varying speech patterns, pitch, tone, language, and accent. Virtual assistants like Amazon Alexa and automatic transcription software use speech recognition to do tasks like these:

+ Assist call center agents and automatically classify calls

+ Convert clinical conversations into documentation in real time

+ Accurately subtitle videos and meeting recordings for wider content reach

**Natural language processing**

Natural language processing (NLP) is the ability to process natural, human-created text. Neural networks help computers gather insights and meaning from text data and documents. NLP has several use cases, including in these functions:

+ Automated virtual agents and chatbots

+ Automatic organization and classification of written data

+ Business intelligence analysis of long-form documents like emails and forms

+ Indexing of key phrases that indicate sentiment, like positive and negative comments on social media

+ Document summarization and article generation for a given topic

**Recommendation engines**

Neural networks can track user activity to develop personalized recommendations. They can also analyze all user behavior and discover new products or services that interest a specific user. For example, Curalate, a Philadelphia-based startup, helps brands convert social media posts into sales. Brands use Curalate’s intelligent product tagging (IPT) service to automate the collection and curation of user-generated social content. IPT uses neural networks to automatically find and recommend products relevant to the user’s social media activity. Consumers don't have to hunt through online catalogs to find a specific product from a social media image. Instead, they can use Curalate’s auto product tagging to purchase the product with ease.

## ↳ How do neural networks work?

The human brain is the inspiration behind neural network architecture. Human brain cells, called neurons, form a complex, highly interconnected network and send electrical signals to each other to help humans process information. Similarly, an artificial neural network is made of artificial neurons that work together to solve a problem. Artificial neurons are software modules, called nodes, and artificial neural networks are software programs or algorithms that, at their core, use computing systems to solve mathematical calculations.
Simple neural network architecture

A basic neural network has interconnected artificial neurons in three layers:

**Input Layer**

Information from the outside world enters the artificial neural network from the input layer. Input nodes process the data, analyze or categorize it, and pass it on to the next layer.

**Hidden Layer**

Hidden layers take their input from the input layer or other hidden layers. Artificial neural networks can have a large number of hidden layers. Each hidden layer analyzes the output from the previous layer, processes it further, and passes it on to the next layer.

**Output Layer**

The output layer gives the final result of all the data processing by the artificial neural network. It can have single or multiple nodes. For instance, if we have a binary (yes/no) classification problem, the output layer will have one output node, which will give the result as 1 or 0. However, if we have a multi-class classification problem, the output layer might consist of more than one output node.

![Neural-Network-Architectures](https://github.com/yagniksorathiya/Neural_Network/assets/129974278/1eb5499b-5437-420d-8b5e-febc3c3753ff)

**Deep neural network architecture**

Deep neural networks, or deep learning networks, have several hidden layers with millions of artificial neurons linked together. A number, called weight, represents the connections between one node and another. The weight is a positive number if one node excites another, or negative if one node suppresses the other. Nodes with higher weight values have more influence on the other nodes.

Theoretically, deep neural networks can map any input type to any output type. However, they also need much more training as compared to other machine learning methods. They need millions of examples of training data rather than perhaps the hundreds or thousands that a simpler network might need.

## ↳ What are the types of neural networks?

Artificial neural networks can be categorized by how the data flows from the input node to the output node. Below are some examples:

**Feedforward neural networks**

Feedforward neural networks process data in one direction, from the input node to the output node. Every node in one layer is connected to every node in the next layer. A feedforward network uses a feedback process to improve predictions over time.

**Backpropagation algorithm**

Artificial neural networks learn continuously by using corrective feedback loops to improve their predictive analytics. In simple terms, you can think of the data flowing from the input node to the output node through many different paths in the neural network. Only one path is the correct one that maps the input node to the correct output node. To find this path, the neural network uses a feedback loop, which works as follows:

1) Each node makes a guess about the next node in the path.

2) It checks if the guess was correct. Nodes assign higher weight values to paths that lead to more correct guesses and lower weight values to node paths that lead to incorrect guesses.

3) For the next data point, the nodes make a new prediction using the higher weight paths and then repeat Step 1.

**Convolutional neural networks**

The hidden layers in convolutional neural networks perform specific mathematical functions, like summarizing or filtering, called convolutions. They are very useful for image classification because they can extract relevant features from images that are useful for image recognition and classification. The new form is easier to process without losing features that are critical for making a good prediction. Each hidden layer extracts and processes different image features, like edges, color, and depth.

**Recurrent neural networks**

Recurrent neural networks (RNNs) are identified by their feedback loops. These learning algorithms are primarily leveraged when using time-series data to make predictions about future outcomes, such as stock market predictions or sales forecasting.

![Type of Neural Networks](https://github.com/yagniksorathiya/Neural_Network/assets/129974278/ecc837b1-9941-4a70-9266-a90fa8033087)

## ↳ How to train neural networks?

Neural network training is the process of teaching a neural network to perform a task. Neural networks learn by initially processing several large sets of labeled or unlabeled data. By using these examples, they can then process unknown inputs more accurately.

**Supervised learning**

In supervised learning, data scientists give artificial neural networks labeled datasets that provide the right answer in advance. For example, a deep learning network training in facial recognition initially processes hundreds of thousands of images of human faces, with various terms related to ethnic origin, country, or emotion describing each image.

The neural network slowly builds knowledge from these datasets, which provide the right answer in advance. After the network has been trained, it starts making guesses about the ethnic origin or emotion of a new image of a human face that it has never processed before.

## ↳ Neural networks vs. deep learning 

Traditional machine learning methods require human input for the machine learning software to work sufficiently well. A data scientist manually determines the set of relevant features that the software must analyze. This limits the software’s ability, which makes it tedious to create and manage.

![simple_neural_network_vs_deep_learning](https://github.com/yagniksorathiya/Neural_Network/assets/129974278/42d78d5d-6635-4988-b18b-f79d496cbe09)

On the other hand, in deep learning, the data scientist gives only raw data to the software. The deep learning network derives the features by itself and learns more independently. It can analyze unstructured datasets like text documents, identify which data attributes to prioritize, and solve more complex problems.

# ➳ Ambient variables ( Environment variables )

![Ambient variables](https://github.com/yagniksorathiya/Neural_Network/assets/129974278/696281ff-b5e6-4760-a762-259fe5f3225e)

Environment variables play a crucial role in Python programming. They provide a way to store and access configuration values, system-specific information, and sensitive data. 

## ↳ What is an Environment Variable?

An environment variable is a named value that can affect the behavior of processes running on a computer system or operating system. It is a dynamic value that is stored in the environment and can be accessed by various programs or scripts running on the system.

Environment variables are typically set by the operating system or by the user and are accessible to all programs and processes running on the system. They provide a way to store configuration settings, system-specific information, or sensitive data without hardcoding them directly into the code. Instead, the code can retrieve the values from the environment variables, allowing for flexibility, security, and portability.

Environment variables are commonly used in software development to configure applications based on the specific environment in which they are deployed. For example, an application may use environment variables to store database connection strings, API keys, file paths, or other settings that can vary across different environments (like development, staging, or production).

In Python, you can access and manipulate environment variables using the os module. This module provides functions and dictionaries to interact with the operating system, including the ability to retrieve the values of environment variables, set new variables, or modify existing ones.

## ↳ How to Access Environment Variables:

To access environment variables in Python, we can leverage the built-in os module, which provides functions for interacting with the operating system

### How to use the os module:

First, we need to import the os module into our Python script:

      import os

The os.environ dictionary allows us to access all the environment variables set on our system. We can retrieve the value of a specific environment variable using its name as the key:

      # Retrieving the value of the "PATH" environment variable
       path = os.environ["PATH"]
       print(path)

### How to retrieve specific environment variables:

To retrieve an environment variable without causing an error if it doesn't exist, we can use the os.environ.get() method. This method takes the variable name as an argument and returns its value. If the variable doesn't exist, it returns None or a specified default value:

       # Retrieving the value of an environment variable with a default value
       database_url = os.environ.get("DATABASE_URL", "localhost:5432")
       print(database_url)

## ↳ How to Set Environment Variables:

We can also set environment variables using the os.environ dictionary.

### How to use os.environ:

To set a new environment variable, we assign a value to a key in the os.environ dictionary:

     # Setting a new environment variable
     os.environ["API_KEY"] = "YOUR_API_KEY"

To modify an existing environment variable, we can simply reassign a new value to the key:

    # Modifying an existing environment variable
    os.environ["DATABASE_URL"] = "new_database_url"

## ↳ Best Practices and Tips for Using Environment Variables:

Naming conventions for environment variables: It is good practice to use uppercase letters and underscores to name environment variables, making them easily distinguishable from regular variables.

Handling platform-specific differences: Keep in mind that environment variable names can differ across platforms. For example, the HOME variable is used in Unix-like systems, while USERPROFILE is used in Windows. Account for such differences when retrieving environment variables.

Documenting and managing environment variables: Maintain documentation that lists all the required environment variables for your application, including their purpose and default values. Utilize tools like .env files to manage environment variables during local development.

Using a .env file for local development: During local development, it's often convenient to use a .env file to store environment variables. This file contains key-value pairs in the format KEY=VALUE, with each variable on a new line. We can use libraries like python-dotenv to load the variables from the file into our Python script automatically.

# ➳ Yield Keyword in Python

![Yield-Keyword-in-Python](https://github.com/yagniksorathiya/Neural_Network/assets/129974278/b41919e6-aa90-4190-a18a-22050e36f329)

Numerous tools in Python make life for programmers much easier. The yield keyword in Python is one such instrument. In typical Python processes, this keyword can be used in place of return statements. We will cover the yield keyword, its use in generator functions, the distinction between a return statement and a yield statement, and the circumstances in which we can use a yield statement in place of a return statement.

## ↳ What is Yield Keyword?

In Python, the generators are the type of function, which are mainly used for the iteration processes. As the name suggests, when called, these functions generate the values or the outputs on the fly, meaning that it works like the iterator and generates values continuously, without stopping.

Same as the conventional function in Python, where the return keyword is used to get the output from the function, in the case of generators the yield keyword is used to generate the temporary outputs, where the execution of the generator function is stopped for temporary basis and can be continued later.

In Python, when the generator function is defined to perform certain tasks related to the iteration processes, the next keyword is used, where the outputs or the values are generated continuously and the function keeps on generating the next values. Once the yield keyword is encountered the function stops from there, here the function saves the current state of the generator and then stops.

Note that when the generator function is resumed again or executed again, the values will start generating from where it left off, not from the starting, as the function saves its state when the yield keyword was encountered.

In short, the yield keywords can be thought of as the breaks for the generator keyword, where the generator stops after this keyword and saves its progress, which is not done in normal or conventional functions. 

![Yield function](https://github.com/yagniksorathiya/Neural_Network/assets/129974278/626a7db8-3b99-4c2c-a1c4-855b351e05f6)

## ↳ Advantages of Yield Function

There are several advantages that the yield function provides when used with the generator functions. Let us discuss that one by one.

**Faster Processes**

As we know that generators are the type of function that keeps on generating the values on the fly. With the help of the yield keyword, we can do the operations faster on the generators. It allows the generators to generate the values immediately for even large datasets.

**Infinite Outputs**

Using the yield keyword with the generators, we can generate the infinite values or the outputs, as it is an iterative process.

**Efficiency**

As discussed, the yield keywords help in generating the values faster for the generator function. Instead of loading the whole data and then generating the same when requested the yield keyword helps generate and process the same without any loading processes.

**Scalable Codes**

When writing codes for the iterative processes, there is a very high chance that the codes mess up and are not scalable, The yield keyword for generators helps in writing efficient and scalable codes, which is easy to understand and interpret as well. 

