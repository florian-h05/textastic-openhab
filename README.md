# Textastic support for openHAB

These files introduce syntax highlighting, templates and __finally__, code-completion for openHAB in the [Textastic iOS App](https://www.textasticapp.com).

Just copy the [```#Textastic```folder](/#Textastic) in the root directory of your Textastic App and enjoy code completion!

## Code completion

Currently, these code completions are supported:
* Items:
    * Full item templating by typing the name of an item type, e.g. ```Switch```, ```Rollershutter```, ```Number```
    * Binding configuration with these parameters:
        * ```channel```
        * ```autoupdate```
        * ```expire```
        * ```homekit```
* Things:
    * KNX device with ```Thing kxn```
    * KNX channel with ```Type knx```