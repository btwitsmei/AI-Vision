# Artificial Intelligence - Vision

## Conceptual development

Artificial Intelligence applied to Vision allows computers to interpret and process images and videos to obtain meaningful information and make decisions based on that information. It is a branch of AI that simulates human visual perception through machine learning algorithms and image processing techniques. In this case, it is not dependent on a platform or cloud service provider, making it easy to deploy in any environment, whether on-premises or in the cloud.


### What is it?

It is a field of science concerned with creating computers and machines that can reason, learn and act in ways that would normally require human intelligence or that involve data whose scale exceeds what humans can analyse.


### How does it work?

This learning process usually involves algorithms, which are sets of rules or instructions that guide AI analysis and decision-making. In machine learning, a popular subset of AI, algorithms are trained on labelled or unlabelled data to make predictions or categorise information.


### Vision 

Machine vision is a field of AI that allows computers and systems to obtain meaningful information from digital images, videos and other visual inputs, and take actions or make recommendations based on that information.


### Benefits 

- **Advanced automation**: Vision AI enables the automation of tasks that require visual analysis, such as quality control, surveillance, facial recognition, etc.

- **accuracy**: algorithms can detect patterns or irregularities with high precision, surpassing many times the capacity of human perception.

- **scalability**: analyse large volumes of images or videos quickly, ideal for applications in industries that handle huge amounts of visual data.


### Disadvantages and limitations

- **computer requirements**: large-scale processing of images and videos can demand high hardware (CPU, GPU) and memory resources.

- **data and training quality**: if accurate data is required, the algorithm needs large amounts of well-labelled data to train correctly, as low-resolution data can affect performance.

- **image quality dependency**: the performance of vision algorithms is highly dependent on the quality of the images or videos for image processing.

- **ambiguity**: in non-optimal conditions (low light, unusual angles, blurred images, etc.) the algorithm may fail or produce erroneous results.


### Alternatives to OpenCV

- **TensorFlow**: Framework used for machine learning, offers a complementary library for vision called TensorFlow Lite which facilitates implementation on mobile and embedded devices (system composed of a combination of hardware and software to perform a specific function).

- **Keras**: Uses TensorFlow as a backend and offers a simplified API for working with neural networks, including pre-trained models for vision such as VGG16 or ResNet.

- **PyTorch**: Direct competitor of TensorFlow, offers advanced tools for building and training large-scale computer vision models, such as the Torchvision library.

- **Dlib**: Library focused on face recognition and machine learning, offering high-precision pre-trained algorithms for face detection and tracking.


### Reasons for using OpenCV

is one of the most popular and efficient options for image processing

- **Versatility**: it covers a wide range of functionalities, from basic image manipulation to advanced computer vision techniques.

- **Community support**: has a large community and documentation support facilitating its use in a variety of projects

- **Performance optimised**: developed in C/C++ with optimisations for use with GPUs, making it efficient for real-time vision applications

- **Easy integration**: compatible with many other AI tools and frameworks, such as TensorFlow or PyTorch, making it easy to combine image processing with deep learning models.


### Differences between AI Vision, AI NPL and AI LLM

||AI Vision | AI NPL |AI LLM
|--|--|--|--|
| **Objective** | enable machines to interpret and understand images and videoss |interaction between computers and human languages|large language models trained on massive text datasets
| **Applications** | facial recognition, image analysis, video surveillance, etc |machine translation, sentiment analysis, text classification, etc|automatic summarization, auto-coding, article generation, etc
| **Techniques** | image processing, image segmentation, and edge detection |syntactic analysis, semantic analysis, and word embeddings|pretraining and fine-tuning on large text datasets


## Technical considerations

The main tools and technical considerations necessary to work with vision AI are detailed. In this case we worked in Python with several open source libraries


### OpenCV:

Open source library specialised in computer vision that includes more than 2500 algorithms. It can be used for image preprocessing as well as for object detection and facial recognition.

> To set up OpenCV, you need to install the required dependencies with the following command </br>
> pip install opencv-python


### MediaPipe:
framework designed to process data streams like videos, offering pre-built solutions for face, hand, and body pose detection. Installing it enables the creation of video processing pipelines and image analysis.

> To install it, run the following command </br>
> pip install mediapipe


### NumPy

NumPy is an essential library for numerical and scientific computing in Python. It is used alongside OpenCV for efficient mathematical operations on image matrices.

> To install it, run the following command </br>
> pip install numpy


> If you want to install all of them at once, run this line: </br>
> pip install opencv-python mediapipe numpy

## Demo link

https://youtu.be/ovcgCNWP5NQ


[in spanish](https://github.com/btwitsmei/AI-Vision/blob/main/README.md)