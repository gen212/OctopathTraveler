Special thanks to turtle-insect for creating this editor.  I've made no serious changes to their code other than to translate the UI into English.

-- njosnavelin/revnja

# Overview
Nintendo Switch OCTOPATH TRAVELER save data editing tool

# Official Game Site
http://www.jp.square-enix.com/octopathtraveler/  
https://octopathtraveler.nintendo.com/  

# Prerequisites
* Windows machine
* .NET Framework 4.7.1 runtime
* Octopath Traveler save file

# Build environment
* Windows 10 (64 bit)
* Visual Studio 2017

# Steps to edit
Acquire save data from Nintendo Switch console.

You should have a set of files that look similar to this:

* KSSaveData 0  
* (KSSaveData 1, KSSaveData 2, ...)  
* KSSystemData  

Save editor will read in KSSaveData (1, 2, 3, etc)  
Perform any editing  
Write out KSSaveData (1, 2, 3, etc) to file  
Import newly edited saveData to Nintendo Switch console

# Special Thanks
* https://gbatemp.net/threads/octopath-traveler-save-editing.511125/
* turtle-insect for creating the original save editor
