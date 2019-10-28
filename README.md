# calibStereo
Stereo calibration with Opencv

Compile all the files using the following commands.

```bash
mkdir build && cd build
cmake ..
make
```
Make sure your are in the `build` folder to run the executables.

### Running
```bash

./calibStereo -w=9 -h=6 -s=0.02423 stereo_calib.xml
