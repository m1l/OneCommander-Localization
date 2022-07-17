# OneCommander-Localization
These are localization files for One Commander file manager.

If your 2-letter language code is not available please contact support@[program name].com and a machine-translated base-file will be provided for an easier start.

Use a free Microsoft's Multilingual app toolkit 4.0 Editor (MAT): 

https://developer.microsoft.com/en-us/windows/downloads/multilingual-app-toolkit/

to open these xlf files so I can re-import them correctly. Please don't use code editor

## Downloading
Method 1: Click green Code button > Download Zip; extract everything
Method 2: Click your language file, click Raw button, and then Save the xlf file 

## Translating
After opening xlf file in "Multilingual app toolkit" (MAT), switch to Strings tab and ignore the Messages tab.

On some message boxes you may see tags like &lt‎;b&gt‎; please keep those and translate only text around.

The keys can be sorted by "Translation state" column (third) to see new or updated keys on top.

Location of a certain string in program can be determined from ID/Key name column. For example "resourcesettings" in ID columns are all from Settings dialog, and should be close to the actual order of the tabs and items in Settings, which might help with translating. Keys name also give clues: the keys starting with DLG_ are dialog boxes, MSG_E are error notifications, _TT are tooltips, etc.

Don't press Enter key in the translated text box as that will result in blank line in translation.

Save often to avoid losing progress if there is a bug in MAT.

The only way to see the results of translation is to compile xlf into dll by the developer. Submit either a pull request or send the translated xlf file to support@[program name].com

Some languages are already maintained by contributors listed in the About dialog and are updated at their schedule. Please contact support or file an issue here before working on a translation because someone might be already working on that particualar language and this would avoid doing a duplicate work. 
