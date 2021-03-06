# Kancolle-bot
---
![LICENSE](https://img.shields.io/github/license/a123453906/Kancolle-bot)

This project is to make the DMM game "Kancolle" easier to play.

Build with Eclipse with [e(fx)clipse](http://download.eclipse.org/efxclipse/updates-nightly/site).

Sorry for the messy code. I will add code comment later to make it more readable.

![Preview](https://i.imgur.com/NNhDug9.png)

## Festures
---
* The Game can run in background(you can do another things when bot is clicking)
* Automatically set off for expeditions.
* Automatically accept expedition missions and clear it.
* Automatically Refresh the mission stat when change day or week.
* Refresh game page when encounter a cat bomb(Working only in [七四式電子観測儀](http://electronicobserver.blog.fc2.com/))
* Configurable random clicking point offset and delay time.
* Action Log
* More infos are in program's "Help" tab

## Using
---
* Require java 1.8.0_102 installed
* Download Kancolle.jar from [Release](https://github.com/a123453906/Kancolle-bot/releases)
* Run it with "javaw -jar Kancolle.jar" or double click on jar

## Troubleshoot
---
delete all ini files in the same path and retry.

## Dependent
---
[SikuliX by RaiMan](http://sikulix.com/)

[JNA 4.4](https://github.com/java-native-access/jna)

## Change Log
---
#### 2020/2/1 v1.0.4 
* FIX: choose expedition page wrong logic.
* DEL: check expedition return when set off expedition and back to HeadQuarter.
#### 2020/1/19 v1.0.3 
* ADD: refresh page when cat bomb function.
#### 2019/12/13 v1.0.2 
* FIX: expedition update. 
* FIX: change BitBlt to PrintWindow method.
#### 2018/10/18 v1.0.1 
* FIX: 2nd Sequence(HTML5) game version corresponding.
#### 2018/1/1 v1.0.0.10 
* FIX: after new year mission function bug.
#### 2017/10/19 v1.0.0.9 
* FIX: officail expeditioning UI updated react.
#### 2017/9/07 v1.0.0.8 
* ADD: quest count function.
#### 2017/7/17 v1.0.0.7 
* ADD: exptime,expnum click select and scroll select support.
* FIX: exp back critical bug and reduce quest checking time.
#### 2017/7/14 v1.0.0.6 
* ADD: HiDPI support.
#### 2017/6/30 v1.0.0.5 
* FIX: when fleet is already expeditioning's expection.
#### 2017/6/25 v1.0.0.4 
* FIX: lots of logic bugs.
#### 2017/6/23 v1.0.0.3 
* improve quest function bugs (beta).
#### 2017/6/13 v1.0.0.2 
* ADD: quest function testing.
#### 2017/6/12 v1.0.0.1 
* FIX: wrong exp time when exp offset time enter negative integer.
* FIX: can't back to home when game is in decoration mode.
* ADD: wait for target timeout setting.
#### 2017/6/11 v1.0.0.0 
* expedition mode completed.











