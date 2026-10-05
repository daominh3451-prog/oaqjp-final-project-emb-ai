# Terminal commands (run inside the project folder: oaqjp-final-project-emb-ai)
# IMPORTANT: the Watson endpoint only works inside the IBM Skills Network Labs environment.

## Task 2 (Activity 2): app imported and tested without errors
python3
>>> from EmotionDetection.emotion_detection import emotion_detector
>>> emotion_detector("I love this new technology")
>>> exit()

## Task 3 (Activity 2): output format
python3
>>> from EmotionDetection.emotion_detection import emotion_detector
>>> emotion_detector("I am glad this happened")
>>> exit()

## Task 4 (Activity 2): package validation
python3
>>> from EmotionDetection import emotion_detector
>>> emotion_detector("I love my life")
>>> exit()

## Task 5 (Activity 2): unit tests
python3 test_emotion_detection.py

## Task 6: run the server, then open the app and take screenshot 6b_deployment_test.png
python3 server.py

## Task 7 (Activity 3): enter a blank text in the web page, screenshot 7c_error_handling_interface.png

## Task 8: static code analysis (must show 10.00/10)
pip install pylint
pylint server.py
