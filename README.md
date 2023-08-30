<h1>Hi 👋, I&#39;m crijun</h1>

<h3>A passionate geek from Austria</h3>

<p><img alt="crijun" src="https://komarev.com/ghpvc/?username=crijun&amp;label=Profile%20views&amp;color=0e75b6&amp;style=flat" /></p>

<p>- 🌱 I&rsquo;m currently learning **all about home automation. Steep learning curve ahead.**</p>

<h2>keypad.yaml</h2>

<p>I want to build an alarm system. Since most of my devices are Zigbee based, I baught a Frient/Develco KEPZB-110 key pad. Found Code which worked from gibhub user AndrejDelany, but it had some things missing (e.g. night arm), some things which I just didn&#39;t like (use code to arm, no night arm mode, SOS button didn&#39;t work, etc.). So I copied the code, minified it and adapted it to my needs. Feel free to steal my code if you want to adapt it. :)</p>

<h3>Behaviour</h3>

<p>You don&#39;t need a code to arm it. I hate overhead.</p>

<p>Buttons:</p>

<ul>
	<li>The key lock button: Arms away the system</li>
	<li>The Home button: Arms home for day usage</li>
	<li>The Moon with clouds button: Arms home for night usage</li>
	<li>SOS button: Needs to be pressed 3x in a row quickly to work, custom action can be configured</li>
	<li>Unlocking with num buttons and open lock: There are 2 options to disarm - 1: Disarm normally with normal pin code und press unlock button - 2: Disarm in emergency mode -&gt; disarms system normally but triggers an additional action that can be configured</li>
</ul>

<h3>Switching between arm profiles</h3>

<p>There is a specific behaviour for switching between arm modes:</p>

<ul>
	<li>Home&lt;-&gt;Night: You can switch with a button press without having to disarm first</li>
	<li>Home/Night-&gt;Away: You can switch with a button press without having to disarm first</li>
	<li>Away-&gt;Home/Night: Needs to be disarmed first before being able to change</li>
</ul>
