# Speech_to_text
Speech to text using Javascript.
languages used - html,css,js.
Speech recognition can be implemented in the browser using JavaScript Web Speech API. The Web Speech API enables the web app to accept speech as
input through the device's microphone and convert the speech into text by matching the words in the speech against the words in its vocabulary.

How do I get voice recognition in JavaScript?
The main JavaScript code which is listening to what user speaks and then converting it to text is this:
// new speech recognition object var SpeechRecognition = SpeechRecognition || webkitSpeechRecognition; var recognition = new SpeechRecognition();
// This runs when the speech recognition service starts recognition.
