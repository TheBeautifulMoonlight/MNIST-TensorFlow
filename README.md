# MNIST-TensorFlow
Using Neural Networks to deal with MNIST data
四个压缩包中分别是训练数据及其标签，测试数据及其标签。
train.py为TensorFlow程序，程序中有自动调用数据包的代码，只要压缩包放在相应的文件夹下。
若相应的文件夹下无数据调用，则此代码会自动下载MNIST数据至此文件夹下。
train.py具体代码理解可见：http://blog.csdn.net/gaoyueace/article/details/79060443
train_improved1.py文件中使用tf.get_variable和tf.variable_scope函数进行优化，代码可读性更高
train_improved1.py具体代码理解可见：http://blog.csdn.net/gaoyueace/article/details/79079068