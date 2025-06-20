# AIML_BigProjects

_Before getting into the projects and the structure let's see some popular tools for Deep Learning_

## Popular DL Tools

Artificial intelligence has acquired the mainstream of business operations. The key reasons behind adopting the AI based techniques for business solution can be listed as:

   - Easy deployment of the solution because of advanced deep learning frameworks.
   - Deep learning framework provide high-level programming interface using which it is quite easy design the deep learning models.
   - The availability of inbuilt libraries has reduced the effort required by the developer

There are many frameworks available for deep learning. The question is, which one to choose?
Following are some of the metrics one can follow while choosing the framework for deep learning:

   - Availability of large number of inbuilt packages in the framework
   - The framework should be able to optimize the performance
   - Should provide parallel computation
   - Framework should have good interface to run the models, lastly
   - The type of the business problem to be solved

Let’s compare deep learning frameworks Keras. Pytorch, Caffe.
### Deep learning in Keras:

   - Keras is open source framework developed by Google
   - Easy to use to build the model
   - Easy to evaluate the model
   - Suitable for beginners as it is user friendly and easy to work with Python
   - It has many pretrained models
   - It supports TensorFlow as the backend and hence model deployment is easy

#### Limitations of Keras:

   - Some of the features in Keras required improvements
   - Since, it is user friendly, it is very slow. So, not suitable for projects where time is important factor
   - Sometimes models developed based on Keras take more time in spite of running it on GPUs. 

### Deep learning in Pytorch:

   - Pytorch is also an open-source framework developed by the Facebook research team
   - It is a pythonic mode of implementing deep learning models
   - All the services and functionalities available in Python environment is available in Pytorch as well.
   - Due to a special feature called auto differentiation the speed is increased in backpropagation process.
   - PyTorch comes has many packages like torchvision, torchaudio, torchtext which can be used to work on NLP, computer vision problems.
   - Pytorch is more useful  for the research than developers.

#### Limitations of Pytorch 

   - Pytorch is more popular among researchers but not preferred by developers.
   - It lacks in production.

### Deep Learning Framework in Caffe

   - Caffe stands for Convolutional Architecture for Fast Feature Embedding.
   - It is ane open-source deep learning framework developed by Yangqing Jia.
   - This framework supports both researchers and industrial applications in Artificial Intelligence.
   - This framework offers good speed
   - Other interesting eature of Caffe is that, it can process 60 million images per day with a single NVIDIA K40 GPU.
   - Many contributors work to update and maintain the frameworks Caffe.
   - Caffe is pore preferred in computer vision models compared to other domains in deep learning.

#### Limitation in Caffe

   - Caffe doesn’t have a higher-level API, so hard to do experiments.
   - In Caffe, model deployment requires each source code to be compile separately.