# Text To Speech Using Computer Installed Voices
[TTS OFF Line](https://github.com/nateshmbhat/pyttsx3) -- uses TTS engines like sapi5, nsss, espeak and installed voices on related Engines

# Virtual ENV and package Installation
windows <br/>
python -m venv folderpackname<br/>
cd folderpackname<br/>
scripts\activate<br/>
pip freeze > installed.txt<br/>
create requirements.txt or use above file<br/> 
add like below for without version number<br/>
pandas<br/>
numpy<br/>
add liike this for versioning<br/>
docopt == 0.6.1             # Version Matching. Must be version 0.6.1<br/>
keyring >= 4.1.1            # Minimum version 4.1.1<br/>
coverage != 3.5             # Version Exclusion. Anything except version 3.5<br/>
Mopidy-Dirble ~= 1.1        # Compatible release. Same as >= 1.1, == 1.*<br/>
package >= 1.0, <=2.0 <br/>
>,>=,<,<=,==,!= etc<br/>

# SELECT INTERPTER IN VSCODE
just copy the path and add \python.exe like D:\python\folderpackname\Scripts\python.exe <br/>

# Install IMAGEMAGICK to use Python
just [download](https://imagemagick.org/script/download.php#windows) WHEN installing ENSURE install legacy utilities CHECKED <br/>
cmd ```convert -version``` <br/>
will give few lines output confirms IMAGEMAGICK installed<br/>
No need of env path<br/>
No need of Python conf.py modification<br/>

