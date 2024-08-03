# Mini-Project-Audio_to_Text

SpeechRecognition is the engine developed by Google.
pydub is used to preprocess the audio file we are using.  

Converting mp3 file to wav format because the installed packages are compatible with that format.

files.upload() can be used if you haven't added the audio file already in the files.

We open the audio file in wav format using pydub and split it in parts wherever the silence is greater then the threshold silence value and these chunks aare added to another file.

The converted audio to text file is converted once the path has been provided and the function is called.
