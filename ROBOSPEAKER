import win32com.client as wincom

if __name__ == '__main__':
    print("*******WELCOME TO ROBOSPEAKER CREATED BY ABHILASH PUROHIT******* ")
    speak = wincom.Dispatch("SAPI.SpVoice")
    while True:
        x = input("Enter what you want to say : ")
        if x == 'q':
            speak.Speak("bye")
        speak.Speak(x)
