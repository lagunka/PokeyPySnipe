###CREDIT TO https://github.com/rubenvereecken/pokemongo-api for providing the API for this repo

This snipe tool will allow you to capture rare pokemon from across the world without being soft banned. It 
works by teleporting to the location of the pokemon, engaging it, teleporting back to your starting position,
and then capturing it. This does NOT trigger a soft ban.

Instructions:
*Install python 2.7.12 from here: https://www.python.org/downloads/

*After install, copy requirements.txt to c:\python27\scripts, open command prompt and type pip install -r requirements.txt
--if you get an error installing flask, run this command and retry installing the requirements: pip install setuptools==21.2.1

*Edit \pogo\snipe.bat with your auth type, username, password and current location (if using google, you MUST put your gmail address / password in the bat file for it to authenticate)

*Run snipe.bat

*After you get the message stating that web server is running on port 5100, navigate to http://localhost:5100

*Paste snipe coordinates (must be xxx.xxxxxx,xxx.xxxxxx format - xxx,xxxxx:xxx,xxxxxxx and other formats do not work at this time)


