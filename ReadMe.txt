jwScrollLoop v1
Jerome "PJ" Williams
https://www.jworksstudios.com/plugins/jwscrollloop
1/22/2013
	
Demo - https://jworksstudios.github.io/jwscrollloop
GIT - https://github.com/jworksstudios/jwscrollloop
	
-GNU Liscense-
-Free to use + tweak. Leave some credit when you can.-
	
About:
This plugin was created because I needed a simple way to animate 
multiple images and divs alike, but I also needed looping 
functionality and additional options without cluttering 


scrollLoop() Options:

'time' : 5000; - The duration it takes to complete the animation (in milliseconds).
'offsetX' : 1000; - The starting X-offset from the original position (in pixels; i.e., 1000px means 1000px to the right from the original position)
'deltaX' : -1000; - The ending X-offset from the original position (in pixels; i.e., -1000px). +value to go right, -value to go left
'offsetY' : 0; - The starting Y-offset from the original position (in pixels; i.e., -1000px = up from the original position)
'deltaY' : 0; - The ending Y-offset from the original position (in pixels; i.e., 1000px). +value to go down, -value to go up
'position_type' : "relative"; The positioning type of the object. Relative or Absolute. Makes a difference in where the object begins and ends.
'play_count' : -1; - The number of times to play the animation. -1 will play infinitely.


Usage:

Setup your elements
<img id="dc1" alt="" src="images/dc1.png" />
<img id="dp1" alt="" src="images/dp1.png" />

Define the actions
<script type = "text/javascript">
$("#dc1").scrollLoop({'time':1000});
$("#dp1").scrollLoop({'time':10000, 'offsetX':-600, 'deltaX':600, 'offsetY':200, 'deltaY':-300});
</script>
