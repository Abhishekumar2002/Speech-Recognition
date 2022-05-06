# Speech Recognition
Speech Recognition is a machine's ability to listen to spoken words and identify them.  
We can use it to convert the input audio to text.  
<br>
Module needs to install:
> [Speech Recognition](https://pypi.org/project/SpeechRecognition/)  
> [PyAudio](https://pypi.org/project/PyAudio/)

***Speech recognition*** library acts as a wrapper for several speech API's and thus extremely flexible. The flexibility and ease of use of Speech Recognition package make it an excellent choice for any python project.  
***PyAudio*** provides python binding for port Audio, the cross-platform for audion I/O library.
<br>
### Step to Run this project in your local system
> 1. Fork the project or download the zip file of the code in your system.  
> 2. Download above mention module using **pip** command in command prompt or pycharm(make sure python is already installed in your local system).  
> 3. Now you can go to the pycharm or Vs Code or any code editior and run the program.  

LET'S SEE THE MAGIC FIRST

https://user-images.githubusercontent.com/104732535/166513859-351439bf-7a2a-416c-8268-db71b4a03704.mp4  

Now, this all magic in speech recognition happens with the *recognizer function*, it recognizes speech from an audio source. So, we create recognizers class. Then we create *microphone function* which take input from mic and convert the voice or speect to text and store the text in a variable. It performs voice recording for arbitrary time using ***PyAudio*** in Python.  
<br>
Then we use *listen function* which listen and store it in audio. After that there is one of the speech recognition engine named ***recognize_google*** in which we gave audio and english Indian language then it will return string which we write as query and the print that query.

