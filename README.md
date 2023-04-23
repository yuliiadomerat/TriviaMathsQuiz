# TriviaMathsQuiz
The application utilizes an Open Source Trivia API to source a diverse array of mathematics-related inquiries, which are subsequently decoded from JSON to Swift. The application also tracks the user's score, providing a final tally upon completion of the 10 questions, and allows for multiple rounds with newly generated questions.

## Short Summary 
- App uses Trivia Open API 
In case no further customization will be made, the Ready-to-Use app uses URL that filteres Trivia questions by Mathematics as a category and is limited to 10 questions.

Used URL: https://opentdb.com/api.php?amount=10&category=19 can be changed under TriviaGameDemo/TriviaManager.swift
If additinal customization of the Questions is required one can generate a new link under: https://opentdb.com/api_config.php

- JSON decoding is already implemented inside the App.
- App is independent of any external platforms, such as Firebase. 
