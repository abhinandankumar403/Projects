# Projects
#1 Speech recognition and search
In this we use library are Speechrecognition, googlesearch,webbroswer and time
#USE CASE 
For recording and getting the text main class is Recognizer.
Recognizer is the class where all the magic happens. 
In the line 6, we initialize the recognizer
In line 9 we started infinte loop so that it runs and we will search things on google just by speaking any time, we can also add a command upon which it starts searching only of there is command in the source sample.
In the line 10 we specifies the source as Microphone we can also add other source file by using the following line
with sr.AudioFile(File name) as source:
Make sure that the file must be in the same folder as of your python program.
