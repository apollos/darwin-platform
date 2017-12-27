# We need an abstract class to define all AI frameworks command line actions:
## 1. data feeding
## 2. training and retrain
## 3. inference
## 4. validation
## 5. parallel job
## 6. Exception handler for all action such as time out, failure and so on

# Need a separate model to manage jobs, such as:
# a) batch jobs for one task
# b) job dependency
# c) kill/cancel job according to task information

# Potential support framework: keras, tensorflow, caffe2

# In this package, we do not consider the neural network model, in the packge, input shall be the ready model file

