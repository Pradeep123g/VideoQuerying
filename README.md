VideoQuerying
=============

Multimedia project- 

-> Designed and developed a java based project where a small video query (clip) is used to search a set of videos and creates a list of
matched videos which contain the “same” or “similar” query.
-> Developed a logic of preparing format for compressed data from the videos which defines the efficiency of this project.



Instructions for running this project file:
-----------------------------------------


-> This is a java file, so it can be executed through normally with an editor like Eclipse etc.
-> This program needs one "query" parameter.

   1) Parameter1: This should be name of the query rgb video file to be given as input to the program.
   

-> Output will contain three windows in an interface, first window showing the input query video, second window showing the output query video and third window showing the name of similar video results that matched with the input query video.

Features provided:
-----------------
1) It can play, pause and stop the videos.
2) Shows similar video results that matched with the input query video.
3) Shows a visual indicator that shows you where in the video you found a match with the query video.


List of files used and their overall summary:
------------------------------------------------
under main folder:
------------------

GlobalValues: All the file path and constant values are defined under this file.
Initialize: It is the main file that triggers the program where the input query video is given as the parameter to this file.  
Transforms: This converts the RGB data to HSV and YUV space.

under controller folder:
----------------------

AudioPlayer: It plays the audio file related to the video.
VideoPlayer: It plays the video file and also controls the corresponding audio file.
MVMetric:    It deals with the Motion vector data and other related fields.


Under view folder:
-------------------

Interface: It is responsible for building the required interface.
ResultGraph: It draws the required graph under the 2nd video.
TimeLine: It shows the match progress of the result video with the input.
VideoPlayerInterface: It configures the graphical positions for the graph.


under model folder:
-------------------

MetadataResults: It maintains the required metadata regarding the videos.
MV data: It contains the set of functions which deal with the MotionVector data.



