# 1. The Hello World of Deep Learning with Neural Networks

A case of creating neural networks, to learns the relationship between two numbers.

## 实现这个操作需要做以下几步：

* 创建神经网络
* 明确Loss function 以及选择优化器（Optimizer）
* 训练神经网络

# 2. First_steps_in_computer_vision
Trained a neural works to recognize different items of clothing from a common dataset called Fashion MNIST.
## Some quesions:
### 1. Experiment with different values for the dense layer with 128 neurons. What different results do you get for loss, training time etc? Why do you think that's the case?
Answer: When increase to 1024 Nerons, training takes longer, but is more accurate.
### 2. Consider the final (output) layers. Why are there 10 of them?
Answer: The number of neurons in the last layer should match the number of classes you are classifying for. In this case it's the digits 0-9, so there are 10 of them, hence you should have 10 neurons in your final layer.
### 3. Consider the effects of additional layers in the network. What will happen if you add another layer between the one with 128 and the final layer with 10?
Answer: There isn't a significant impact -- because this is relatively simple data. For far more complex data, extra layers are often necessary.
### 4. Consider the impact of training for more or less epochs. Why do you think that would be the case?
Answer: Try 15 epochs -- you'll probably get a model with a much better loss than the one with 5. 
        Try 30 epochs -- you might see the loss value stops decreasing, and sometimes increases. This is a side effect of something called 'overfitting' which you can learn about [somewhere] and it's something you need to keep an eye out for when training neural networks. There's no point in wasting your time training if you aren't improving your loss,

# 3. Handwriting recognition
Trained a neural works to recognize different hanwritten digits from a common dataset called MNIST.
