## API Outage (Temp fix)
API are down that are deeply connected with the server and in the way how keybox validation works due to reports by Google. Google detected "too many requests" on taking integrity checks so it will take some time for me to recover it.

Please, do not share sensitive information about tests you do and please do not do integrity checks often so that we can keep this project working as expected.

(While working on a fix, I've linked external sources to provide strong so you guys don't need to worry about strong for now. Just keep in mind, don't check for integrity too much and don't share sensitive information about those tests to avoid more bans)

# Tricky Store Addon (WIP)
This is Tricky Store addon created to extend features of original TrickyStore! The base of this module is [Tricky Store Helper](https://github.com/CaptainThrowback/TrickyStoreHelper) by Captain_Throwback.

## Implemented Features
1. In-real-time updating target.txt file

2. Updating the module in root managers directly

3. [Get-Keybox](https://github.com/joeyoropesa-dev/trickystore-addon#get-keybox-implementation-wip) for getting valid keybox.xml files after each boot as soon the internet connection is established

## To-do list
1. ~~Getting non-revoked valid keybox.xml files in-real-time (as soon you get connected to the internet after each boot)~~ Done :)

2. Python support

3. You tell me :)

## Requirements
1. Latest Tricky Store by [5ec1cff](https://github.com/5ec1cff/TrickyStore)
2. Latest root manager (KSU/APatch/Magisk)
3. Stock ROM (Since most custom ROMs failing to pass Play Integrity)
4. Play Integrity Fix by [Chiteroman](https://github.com/chiteroman/PlayIntegrityFix) (Optional)

## Get-Keybox Implementation (WIP)
Get-Keybox is a feature implemented in module that allows getting non-revoked latest keybox as soon the boot is completed and network connection is established. You can also manually execute the command
```console
:/ $ su
:/ # getkb
```
to re-download latest keybox from our server without needing to reboot your device.

The WIP (Work-in-progress) flag is set to this feature since it's in early stages so expect bugs and issues and report them - [#Issues](https://github.com/joeyoropesa-dev/trickystore-addon/issues)

#

## Issues, Questions, Suggestions..
Since I have both Issues and Discussions tabs opened, please use correct places to suggest, ask questions and report issues/bugs.

## Donation
You can subscribe to [Patreon](https://www.patreon.com/joeyoropesa) and help me financially
