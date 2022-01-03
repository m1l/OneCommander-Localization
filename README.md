# OneCommander-Localization
These are localization files for One Commander file manager

If your 2-letter language code is not available please contact support@[program name].com and an automatically translated base file (using Bing Translator) will be provided for easier start.

Please don't use code editor for editing these - use Microsoft's Multilingual app toolkit 4.0 Editor (MAT)
https://developer.microsoft.com/en-us/windows/downloads/multilingual-app-toolkit/
to open these xlf files so they can be imported correctly.

## Translating
After opening xlf file in MAT, switch to Strings tab and ignore the Messages tab.

On some message boxes you may see tags like "<bpt id="1">&lt;b&gt;</bpt>"; please keep those and translate only text in and around it.

Keys can be sorted by "Translation state" column (third) to see first new or updated keys.
Location of certain string in program can be determined from ID/Key name column. For example "resourcesettings" in ID columns are all from Settings dialog, and should be close to the actual order of the tabs and items in Settings, which might help with translating. Keys starting with DLG_ are dialog boxes, MSG_E are error notifications, _TT are tooltips, etc.

Save often to avoid losing progress if there is a bug in MAT.

The only way to see the results of translation is for these to be compiled into a dll resources. Either submit pull request or send the translated xlf file to support@[program name].com

Some languages are already maintained by contributors listed in the About dialog and are updated at their schedule.

