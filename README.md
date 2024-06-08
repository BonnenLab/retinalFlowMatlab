# retinalMotion
approximate retinal flow from precomputed .flo files and gaze data


## Getting started with retinal optic flow

0. install requirements 
	a. python .yml TODO
	b. matlab
		- 

1. Undistort video

2. Use deep flow to calculate head-centered optical flow

	python openCVOF2.py <output-dir> <video-file> <maxFrames> <res>

	python openCVOF2.py output-dir/ video.mp4 9999 720x1280

3. Set the config strings at the top of main.m
