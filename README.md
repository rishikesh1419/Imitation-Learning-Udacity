# Imitation-Learning-Udacity

## Simulator
[Udacity Open Source Simulator](https://github.com/udacity/self-driving-car-sim)
(Use Term 1 simulator)

## Dependencies
- python
- numpy
- matplotlib
- jupyter
- opencv3
- pillow
- scikit-learn
- scikit-image
- scipy
- h5py
- eventlet
- flask-socketio
- seaborn
- pandas
- imageio
- pip
- moviepy
- tensorflow-gpu
- keras

### You might have to add these channels to Anaconda environment
- https://conda.anaconda.org/menpo
- conda-forge

## How to use
Start the simulator in manual mode and press "R" to start recording. Drive for around 3-5 laps.
A dataset will be generated with 3 images for each instance and corresponding throttle, steering angle, brake and speed.  

Run the model.py file.
```
python model.py
```

During training, .h5 files will be created.
To simulate the car, start the simulator in autonomous mode run the drive.py file.
```
python drive.py <model file>
```

## Credits

The original code was written by [naokishibuya](https://github.com/naokishibuya).  
I've modified it to work with newer versions of libraries.
