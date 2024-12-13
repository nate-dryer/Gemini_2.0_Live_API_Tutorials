# Gemini_2.0_Live_API_Tutorials  

These two Python files provide a demo of the newly release Google Gemini 2.0 Live API.  

## live_api_starter_cv.md  
The Live API Starter is a Python application that implements real-time audio and video interaction with Google's Gemini AI model. It creates a bidirectional communication channel where users can send text, audio, and video input while receiving audio and text responses from the model in real-time.  
The code shares the video from your webcam with the Gemini model, while you can also do a voice chat.  

## live_api_starter_desk.py  
This application is a desktop assistant that combines audio input/output capabilities with screen capture functionality to interact with Google's Gemini API. It creates an interactive experience where users can communicate with the Gemini model through both voice and text while sharing their screen.  
The code shares your desktop with the Gemini model, while you can also do a voice chat.  

# References:  
	https://github.com/google-gemini/cookbook/blob/main/gemini-2/README.md  
	https://github.com/google-gemini/cookbook/blob/main/gemini-2/live_api_starter.py  

## The new Gemini 2.0 Live API requires:  
	https://pypi.org/project/google-genai/  
	https://github.com/googleapis/python-genai  

To learn more, see the Python SDK reference:  
	https://googleapis.github.io/python-genai/  

# Possible bugs  
During testing I've noticed that the Gemini model sometimes fails to "see" the webcam or the desktop when you request that via the text prompts, however, it usually works well if you make the same request via the voice prompt.  
This might be due to the nature of the experimental release at the time of the tests.  

# Please note  
The code is provided as-is for learning purposes, please don't expect any updates in the future.  
I've made some changes to the code in the Google cookbook to add some logging and troubleshooting details.  
This code was tested with Python 3.12 running on Windows 11.  
Unfortuantely, I can't provide any support.  
