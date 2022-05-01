# Speech-Recognition
import speech_recognition as s
#create a object of recognizer
sr = s.Recognizer()

print("I am your script and listening you....................")

with s.Microphone() as m:
    audio = sr.listen(m)
    text = sr.recognize_google(audio, language='en-IN', show_all=True)
    print("I thinks you said '" + sr.recognize_google(audio) + "'")
