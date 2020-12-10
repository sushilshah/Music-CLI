<div align = "center">
<img src="images/logo.jpeg" width=300px/>
 </div>
<div align="center">
 
<div align = "center">
<img src="https://img.shields.io/badge/-GoLang-white?style=for-the-badge&logo=go" width=150px/>
 </div>
 


<br>



</div>

------------------------------------------

> **Music-CLI** is a command line Music Player, written in Go! 

> It allows you to enjoy music by just typing a single command.



------------------------------------------

### Scope

* Its one of the most important feature is that it does not require internet so no more wasting money on internet.
* You just need to have a song in your PC and boooom you’re good to go !

------------------------------------------
### Libraries Used

<img src="images/beep.png" width=100px/>

* Beep 
- [x] Used for playing audio files .

<img src="images/tcell.png" width=100px/>

* TCell
- [x] Used for laying out interface on terminal. 

### List of Features 

* Control Music Playback
- [x] Play/Pause/Stop.
- [x] Rewind/Fast Forward.
- [x] Change Playback speed.
- [x] Playback Volume.

------------------------------------------
<div align = "center">

<img src="rec.gif" width=600px/>
<br/><br/>

</div>

------------------------------------------

### Steps for Project Execution :

##### Install Required Packages:
```
1. Beep - go get -u github.com/faiface/beep
2. TCell - go get -u github.com/gdamore/tcell
```
##### To Run:
```
1. Open terminal
2. Enter:
    go run music-CLI.go ./song.mp3
    This will play the audio on the CLI !
```


