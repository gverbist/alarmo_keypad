<h1 align="center">Hi 👋, I'm crijun</h1>
<h3 align="center">A passionate geek from Austria</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=crijun&label=Profile%20views&color=0e75b6&style=flat" alt="crijun" /> </p>

- 🌱 I’m currently learning **all about home automation. Steep learning curve ahead.**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h2>keypad.yaml</h2>

<p align="left">I want to build an alarm system. Since most of my devices are Zigbee based, I baught a Frient/Develco KEPZB-110 key pad. Found Code which worked from gibhub user AndrejDelany, but it had some things missing (e.g. night arm), some things which I just didn't like (use code to arm, no night arm mode, SOS button didn't work, etc.). So I copied the code, minified it and adapted it to my needs. Feel free to steal my code if you want to adapt it. :)</p>

<h3>Behaviour</h3>

<p align="left">
You don't need a code to arm it. I hate overhead.

Buttons:
The key lock button: Arms away the system
The Home button: Arms home for day usage
The Moon with clouds button: Arms home for night usage
SOS button: Needs to be pressed 3x in a row quickly to work, custom action can be configured
Unlocking with num buttons and open lock: There are 2 options to disarm
  - 1: Disarm normally with normal pin code und press unlock button
  - 2: Disarm in emergency mode -> disarms system normally but triggers an additional action that can be configured
</p>

<h3>Switching between arm profiles</h3>

<p align="left">
There is a specific behaviour for switching between arm modes:
Home<->Night: You can switch with a button press without having to disarm first
Home/Night->Away: You can switch with a button press without having to disarm first
Away->Home/Night: Needs to be disarmed first before being able to change
</p>
