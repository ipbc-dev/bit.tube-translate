Dear community, 

Here is your opportunity to help us make a better platform.  We need your help translating the site into all possible languages.  If you are a native speaker you can help by translating the site to your native language, this will ensure our site can be surfed by non-English speaking people.  

Inside of our Github repository, you can find our translate section ( https://github.com/ipbc-dev/bit.tube-translate ), and inside the repository you will find our English version translation file in json format, we have called it en-en.json.

Naming convention:  
To create a new language file, simply copy the existing en-en.json file locally, and rename it to the language you want to translate to.  The file name convention is a combination of minor language, hyphen, major language and extension (minor-major.json).
For example an Italian file would be named it-it.json, and French would be fr-fr.json, US would be us-en.json and so on.

How to complete the language file:
The language files follow the following structure, where the screen name is followed by a name / value pair.
The name value pair holds the variable name followed by the translated text, for example:

"Title": {
	        "var1": "translated text",
	        "var2": "translated text",
			…
      
      
In the above example, the member translating the file would change the value “translated text” to the appropriate word or phrase in the translated language.  once a file is completed, we would just plug it into the site thus serving the content in that language. 

Thank you in advance for your participation.
