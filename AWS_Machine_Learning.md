# Machine Learning Scientist

## Introduction

Topics:

- Define Machine Learning
- Application and problem solving capabilities of Machine Learning
- Identify core competencies needed in Machine Learning
- Identify career options in the field of Machine Learning

- [Machine Learning at AWS](https://aws.amazon.com/machine-learning/what-is-ai/)

## The AWS ML Stack

There are essentially three layers in the stack:

1. API-based services designed for application development.

2. Platform services designed for data scientists.

3. Frameworks/Infrastructure services designed for advanced/deep learning data scientists.

![AWS ML STACK](awsmlstack.PNG)

## API-based services

### [Amazon Rekognition](https://aws.amazon.com/rekognition/)

- Amazon Rekognition makes it easy to add image and video analysis to your applications using proven, highly scalable, deep learning technology that requires no machine learning expertise to use. With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as detect any inappropriate content. Amazon Rekognition also provides highly accurate facial analysis and facial search capabilities that you can use to detect, analyze, and compare faces for a wide variety of user verification, people counting, and public safety use cases.

### [Amazon Polly](https://aws.amazon.com/polly/)

Amazon Polly is a service that turns text into lifelike speech, allowing you to create applications that talk, and build entirely new categories of speech-enabled products. Polly's Text-to-Speech (TTS) service uses advanced deep learning technologies to synthesize speech that sounds like a human voice.

### [Amazon Lex](https://aws.amazon.com/lex/features/)

- [Getting Started](https://aws.amazon.com/lex/getting-started/)
- Powered by the same technology as Alexa, Amazon Lex provides you with the tools to tackle challenging deep learning problems, such as speech recognition and language understanding, through an easy-to-use fully managed service. Amazon Lex integrates with AWS Lambda which you can use to easily trigger functions for execution of your back-end business logic for data retrieval and updates. Once built, your bot can be deployed directly to chat platforms, mobile clients, and IoT devices. You can also use the reports provided to track metrics for your bot. Amazon Lex provides a scalable, secure, easy to use, end-to-end solution to build, publish and monitor your bots.

### [Amazon Translate](https://aws.amazon.com/translate/)

- Amazon Translate is a neural machine translation service that delivers fast, high-quality, and affordable language translation. Neural machine translation is a form of language translation automation that uses deep learning models to deliver more accurate and more natural sounding translation than traditional statistical and rule-based translation algorithms. Amazon Translate allows you to localize content - such as websites and applications - for international users, and to easily translate large volumes of text efficiently.

## Platform Services

### [Amazon Sagemaker](https://aws.amazon.com/blogs/aws/sagemaker/)

- Amazon SageMaker is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models.

- Traditional ML development is a complex,expensive, iterative process made even  harder because there are no integrated tools for the entire machine learning workflow. You need to stitch together tools and workflows, which is time-consuming and error-prone. SageMaker solves this challenge by providing all of the components used for machine learning in a single toolset so models get to production faster with much less effort and at lower cost.

![](sage.PNG)

### [Amazon DeepLens](https://aws.amazon.com/deeplens/)

AWS DeepLens helps put machine learning in the hands of developers, literally, with a fully programmable video camera, tutorials, code, and pre-trained models designed to expand deep learning skills.

Kay Notes : Basically a very cool machine learning based camera but will be costly given this is amazon lol.

### [Amazon Machine Learning](https://docs.aws.amazon.com/es_es/machine-learning/latest/dg/tutorial.html)

## Frameworks and Infrastructure

### Develop sophisticated models with any framework

AWS supports every major deep learning framework to provide data scientists and developers with the most open and flexible environment. The frameworks and infrastructure (hardware/services) layers of the ML stack are for data scientists. These two layers are typically grouped together because this is where the super deep experts want to play. These layers make deep learning very accessible by providing choice. These frameworks are environments where you build deep learning.

### [Amazon Deep Learning AMIs](https://aws.amazon.com/machine-learning/amis/)

- The AWS Deep Learning AMIs provide machine learning practitioners and researchers with the infrastructure and tools to accelerate deep learning in the cloud, at any scale. You can quickly launch Amazon EC2 instances pre-installed with popular deep learning frameworks and interfaces such as TensorFlow, PyTorch, Apache MXNet, Chainer, Gluon, Horovod, and Keras to train sophisticated, custom AI models, experiment with new algorithms, or to learn new skills and techniques.

Whether you need Amazon EC2 GPU or CPU instances, there is no additional charge for the Deep Learning AMIs – you only pay for the AWS resources needed to store and run your applications.

___Kay Notes : This can be Useful to Student Developers___

- [Tensorflow on Aws](https://aws.amazon.com/blogs/machine-learning/zocdoc-builds-patient-confidence-using-tensorflow-on-aws/)
- [Tutorials](https://docs.aws.amazon.com/dlami/latest/devguide/tutorials.html)

### MXNet and TensorFlow

Apache MXNet (Links to an external site.) is a fast and scalable training and inference framework with an easy-to-use, concise API for machine learning. MXNet includes the Gluon (Links to an external site.) interface that allows developers of all skill levels to get started with deep learning on the cloud, on edge devices, and on mobile apps. In just a few lines of Gluon code, you can build linear regression, convolutional networks and recurrent LSTMs for object detection, speech recognition, recommendation, and personalization.

TensorFlow (Links to an external site.)™ enables developers to quickly and easily get started with deep learning (Links to an external site.) in the cloud. The framework has broad support in the industry and has become a popular choice for deep learning research and application development, particularly in areas such as computer vision, natural language understanding and speech.

## Core Competencies

- Machine Learning Scientists work in the research and development of algorithms that are used in adaptive systems. For example, they build methods for predicting product suggestions (recommendations) and product demand (forecasting), and explore Big Data to automatically extract patterns (large-scale machine learning and pattern recognition). Some Machine Learning positions include Machine Learning Scientist, Research Science Manager, and Data Sciences Lead.

Cool Links to useful resources for ML

- [ML GUY NEEDS](https://blog.udacity.com/2016/04/5-skills-you-need-to-become-a-machine-learning-engineer.html) __Look__
- [Decriptive Stats](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
- [Inferential Stats](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)
- [18.06 LinAlgebra](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/)
- [Calculus](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/) __Look__
- [Probability and Stats](https://www.edx.org/course/probability-the-science-of-uncertainty-and-data)
- [Data Modeling](https://www.edx.org/course/data-science-inference-and-modeling) __Look__

## AWS Specific Competencies

- Compute: [AWS EC2 Instances](https://aws.amazon.com/ec2/instance-types/)
- Storage: [Cloud Storage](https://aws.amazon.com/products/storage/?nc2=h_l3_db)
- Database: [Purpose built databases](https://aws.amazon.com/products/databases/?nc2=h_l3_db)
- Analytics: [Analytics Services AWS](https://aws.amazon.com/big-data/datalakes-and-analytics/)

### AWS Publuc Datasets

- AWS hosts a variety of public datasets.When data is made publicly available on AWS, anyone can analyze any volume of data without needing to download or store it themselves. These datasets can be analyzed using AWS compute and data analytics products.
- [AWS Public Datasets](https://registry.opendata.aws/)

Cool Links Specific to ML when on AWS:
- [Neural Nets Uncool AWS Style](https://aws.amazon.com/blogs/machine-learning/making-neural-nets-uncool-again-aws-style/)
- [Machine Learning at Your Startup](https://youtu.be/5_LNHWgsYo4)
- [ML and AI on AWS](https://aws.amazon.com/blogs/machine-learning/now-available-new-digital-training-to-help-you-learn-about-machine-learning-and-artificial-intelligence-on-aws/)
