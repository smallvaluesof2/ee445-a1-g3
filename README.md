# ee445-a1-g3

The circuit diagram for the ECG soo far is here
![ecgcircuit](https://user-images.githubusercontent.com/26180784/37901461-2bc4cfc8-30e9-11e8-9ae0-4a892d089591.png)

Changes I suggest we can try after testing on the Oscilliscope are to the High pass and low pass filter.
Currently the High Pass filter is allowing frequencies above 0.03Hz. 
But we may need to adjsut this to a cut off of 0.5Hz if muscle smovement signals seem to be a problem

The low pass filter is cuting out any frequencies above 40Hz. We may lose some of the ECG QRS signal features at this cut off.
To improve this we can increase it to 50Hz which should allow all QRS elements be captured.

The calc for cut off is 1/2(pi)RC for both filters.
