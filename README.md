# Personal-Assistant-application
C++ text to speech application which acts as a personal assistant. 

Firstly one must download and install espeak speech synthesizer. 
If you need to listen to the speech, then you must include these 4 lines of code:

string phrase = "whatever message you want to listen to";
string command = "espeak \"" + phrase + "\"";
const char *charCommand = command.c_str();
system(charCommand);

To open a browser:
system("start url of browser");
Example:
system("start https://www.youtube.com");

