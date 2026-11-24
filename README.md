# OneCommander-Localization
These are localization files for OneCommander file manager.

If your 2-letter language code is not available please contact support@[program name].com and a machine-translated base-file will be provided for an easier start.

<s>Use a free Microsoft's Multilingual app toolkit 4.0 Editor (MAT): 

https://developer.microsoft.com/en-us/windows/downloads/multilingual-app-toolkit/ </s>
(Microsoft discontinued MAT)

Please use free Poedit https://poedit.com/download/ or any other CAT tool that can open these xlf files so I can re-import them correctly. Please don't use code editor

## Downloading
Method 1: Click green Code button > Download Zip; extract everything
Method 2: Download both files for your language: click each file, click Raw, and save the xlf file. 

## Translating
For your language, open and update both `Rapidrive.<language>.xlf` and `OCTaskmaster.<language>.xlf`. For example, translate both `Rapidrive.fr.xlf` and `OCTaskmaster.fr.xlf` for French. Submit both files when you finish.

Program is very simple to use - it has list of keys and translation box

On some keys you will see something like "🡢" or "&lt‎;b&gt‎;" or [NEWLINE]. Please copy paste the entire text in translation box and just translate around those elements to avoid mistakes or retyping 

Don't press Enter key in the translated text box as that will result in blank line in translation and shift some elements below.

Save often to avoid losing progress if there is a bug in translation program.

The only way to see the results of translation is to compile xlf into dll by the developer. Submit either a pull request or send both translated xlf files to support@[program name].com

Some languages are already maintained by contributors listed in the About dialog and are updated at their schedule. Please contact support or file an issue here before working on a translation because someone might be already working on that particualar language and this would avoid doing a duplicate work. 
