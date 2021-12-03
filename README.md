# Dancing Horse

![Image](/myLittePony.jepg)

## Usage


### 1. Open the html file with Window Browser(e.g. Chrome)

### 2. Set the parameter according to your environment.  

we had been set the some parameter values as default, however, you can change input value according to your environment.

- Start Size: the size of images when it start to move.

- End Size: the size of the images when it arrived to the end of the browser.
* (e.g. If you set start size: 300, and end size as 500, images becomes bigger inclemently in each duration.)


- Height(Start/End): Height of the images when start and end.

- Speed(ms):speed of the images move in each duration.


### 3. Press 'Start'



## Test Scenarios

Since we are using position-based tracking algorithms, we having jerky issue. And it brings Jerky issue which means when object is located in center, pod always stop and moving again, so it make tracking is not smoother.


Steps to reproduce

Pre conditions: 
- Target speed set as slow: 10000 ~ 15000 (ms)
- Pod speed set as frenzy(max speed 6s/r)

Test Case: Since we had implement different sensitivity according to the different zoom level, need to test in different zoom level

1. Zoom level x1

2. Zoom level x3

3. Zoom level x4 


