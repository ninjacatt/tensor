1. Install Tensorflow https://www.tensorflow.org/install/
2. Go to virtual environment: >> source ~/tensorflow/bin/activate
3. Inside the virtual env Install Jupyter notebook: >> pip install jupyter notebook
4. Launch the notebook: >> jupyter notebook

#Run python and tensorboard:
1. Have our python ready (for example, basic_math.py)
2. In virtual environment, run: python basic_math.py 
This will create an event file (for tensorboard) in our logs folder
3. In virtual env, run: tensorboard --logdir="/Users/username/tensorflow/notebook/logs"
4. open http://localhost:6006/ to view the board
