<style>
body {
background-color: DarkSlateGray;
color: white;
}
/* unvisited link */
a:link {
  color: whitesmoke;
}

/* visited link */
a:visited {
  color: snow;
}

/* mouse over link */
a:hover {
  color: ghostwhite;
}

/* selected link */
a:active {
  color: white;
}
</style>
<title>How to see the camera</title>
<link rel="shortcut icon" type="image/ico" href="Pogpega.ico"/>

# HOW TO SEE THE CAMERA  
I use an IP camera that makes an rtsp stream which can be accessed on vlc or some other rtsp player or something.  

### Step 0: Get VLC  
If you don't already have it, get VLC media player (or if you know what you're doing and already have an rtsp player thing then use that I guess)  

### Step 1: do the thing  
Go to Media &gt; Open Network Stream  
![where the thing is](https://i.imgur.com/tQyZUvN.png)  
  
Where it says enter a network URL put in this:  
rtsp://Pogpega:Pogpega1234@pogpega.duckdns.org:554/stream1  

### Step 2: Press play  
Press play.  
If it doesnt work I probably haven't updated my IP on duckdns  