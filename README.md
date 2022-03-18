# real-time_optical_flow_tracking

## [Optical_Flow_Tracking](https://github.com/vishal-kasyap/optical_flow_tracking_on_recorded_video.git)



    https://github.com/vishal-kasyap/optical_flow_tracking_on_recorded_video.git
            
            
           
The above mentioned repo gives an introduction about Optical Flow Tracking, Types and their Implementation using OpenCV.

This repo is an extension of it, where same algorithms are used on a realtime data rather than on a pre-recorded video.

## Steps:

  1. Apart from this [repo](https://github.com/vishal-kasyap/optical_flow_tracking_on_recorded_video.git), only one small modification is to be done to work with the algorithm in realtime.
  2. Instead of specifying the path of the video in __*cv.VideoCapture*__, specify a number. 
  3. The number is 
 
         a. "0" [default value if there is an inbuilt camera] 
         b. "1" or "2" or "3" [according to the port with which the external camera is connected] 
                              [can be found using trial and error method]
               
               
# Note:

   1. It is duly noted that, if the resolution of the external camera is very high (say, 720p or 1080p or higher), then there are high chances to get an error.
   2. This is because there is an increase in the number of pixels and so the computation may or may not be possible.
