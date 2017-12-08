to run this: 
sudo -H pip3 install tensorflow-1.4.0-cp36-cp36m-linux_x86_64.whl

to confirm:

python3
```
import tensorflow as tf
hello - tf.constant('Hi TF!')
sess = tf.Session()
print(sess.run(hello))


now assuming you don't get any comment about The TensorFlow library wasn't compiled to use SSE4.1 instructions, but these are available on your machine and could speed up CPU computations you are good to go! (the whole purpose of using this wheel is to get that very speed up (and not to have to build from source or install bazel....))

Righteous! 
