# realtime-music-viz
Use this tool to create configurable music visualization effects by defining how audio processing code drives a light control interface.

The project consists of three main components:
-a process that performs audio processing (filtering, beat detection...)
-a process that controls light sources (brightness, color, on/off...)
-a process that connects the audio processing process outputs to the light control process inputs

Project design goals:
-code is agnostic to whether the three components are running on the same machine or not
-any kind of digitally controllable light source can be connected

