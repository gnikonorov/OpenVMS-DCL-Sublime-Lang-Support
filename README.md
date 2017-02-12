This project contains the necessary files to create support for the openvms flavor of DCL.

Sublime uses the text mate language grammar when constructing syntax highlighting schemes. The documentation for this can be found here: http://manual.macromates.com/en/language_grammars.
	Specifically, each name entry corresponds to a name entry as outlined in section 12.4, with the name of the language extention at the end ( in this case 'com')

Development of the language grammamar highlighting scheme was sped up significantly through the use of YAML to develop and not through plists directly. A Sublime package exists that converts YAML to plists, and it is called 'PackageDev'. Please see https://github.com/SublimeText/PackageDev for installation and use notes.