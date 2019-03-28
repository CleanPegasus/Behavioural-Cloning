# Behavioral Cloning

This project aims at making an autnomous car driving simulation on the udacity simulator.

<img src="readme resources/drive.gif">
</img>




## Requirements :

> **Use Google Colab for running the model**

> Udacity Self-driving car simulator :

[Windows](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f3a4_simulator-windows-64/simulator-windows-64.zip)
[Mac](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f290_simulator-macos/simulator-macos.zip)
[Linux](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f0f7_simulator-linux/simulator-linux.zip)

> [Python 3](https://www.python.org/downloads/)

Open command prompt or terminal and type the following commands to install the respective libraries.

> Socket io : ```pip3 install python-socketio```

> Flask : ```pip3 install flask```

> Keras : ```pip3 install keras```

> Tensorflow : ```pip3 install tensorflow```

> OpenCV : ```pip3 install opencv-python```

> Pillow : ```pip3 install pillow```

> Numpy : ```pip3 install numpy```

> Eventlet : ```pip3 install eventlet```

## Instructions :
Download and run the udacity simulator from the link given above. Open the training mode. Get used to the drving track and start recording your driving and save it in a data file.

Try to drive the car in the middle of the road as much as possible. Drive atleast 3 laps in both clockwise and anti-clockwise directions for proper data collection.

Open **Google Colab** and upload the Behavioral_Cloning.ipynb file.

Import the data into the Behavioral_Cloning.ipynb file and run it (Or you can use the pre-existing data).

The Nvidia model works best for the Behavioral Cloning of autonomous car. Feel free to experiment with different parameters and preprocessing techniques.

 Download the model and paste it in the same folder as the Drive.py file.

 Now run the Drive.py code and open the Udacity simulator on **Autonomous** mode. Your terminal will show it's connected and the car will start moving based on the model.


<img src="readme resources/drive 1 .png">
</img>
