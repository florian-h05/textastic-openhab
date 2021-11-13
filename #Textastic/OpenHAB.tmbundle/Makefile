TM_LANGUAGE = Syntaxes/OpenHAB.tmLanguage
JSON = https://raw.githubusercontent.com/openhab/openhab-vscode/a59a95706f2491f5bc51e4b7bbf1785257b7a5c2/syntaxes/openhab.tmLanguage.json

all: $(TM_LANGUAGE)

$(TM_LANGUAGE):
	mkdir -p $(dir $(TM_LANGUAGE))
	curl -L $(JSON) | plutil -convert xml1 - -o $@
	/usr/libexec/PlistBuddy -c "Add :uuid string 'a3362938-3db0-4143-925c-644cf3b8d8a2'" $@
