<h1 style="color:red;"> TODO </h1>
<p> Create away to automatacly convert tilemaps.</p>
<p> Add Godot 4.4 tilemap compatibility</p>
<p> Add more node conversion names</p>
<p> Fix node placement when converting over</p>
<p> Make 3D conversion convert properly</p>

<h1>About this project</h1>
<p>This began as a way for me to play my godot games on xbox, without having to re-program my code all for godot 3, and to make it so that I don't have to make a custom godot 4 build with UWP support. However, I now realise that this can also be used with HomeBrodot, which allows you to port your godot 3 games to swich and PSP! (PS, this was originally made in godot 4.4)</p>

<h3>How to use</h3>
<p>I am terrible about making tutorials but here I go</p>
<p>either make a folder and/or place your Godot 4.3 and under project into the "import" folder</p>
<p>if it's your first time loading this, check "copy all files"</p>
<p> and hit convert! it's that easy!</p>
<p>you may need to add a project.godot file, but you whole project can load currently with a bunch of issues</p>


<br></br>

<h2>Just know that I am very open to people adding to this, and if you know how to make the tilemap conversion, please make a fork and I'll most likely add it to this. If you just want to use it to convert your projects, anything that requires custom data will not work yet, as this is not complete. I know the way i'm doing this is VERY weird, but it gets the job done</h2>


<h1>Compatible Versions</h1>
<h2>2D</h2>
<h3>Godot 4.3<  -- Almost there.</h3>
<p>  While things are looking good so far, with a majority of things being passed down to 3.5, Tilemaps still need to be manually edited, fonts do not convert, some nodes need to be re-created. (if I can)</p>
<h3>Godot 4.4+ -- Far from working</h3>
<p>  In Godot 4.4, there was a change to how asset storage works. so a LOT of assets like tile maps have data that cannot be read, furthermore I don't know how to convert it back... I know it's possible I just can't figure it out</p>

<h2>3D</h2>
<h3>Godot 4.3< -- still needs work</h3>
<p>  3D is turning out to be a harder task than initally thought out to be, The ResourceLoader has had a HUGE overhaul, which makes any attempt to use it impractical. Will be looked into in the future. 3D assets are not being properly imported currently as I just started work a couple days ago</p>
<h3>Godot 4.4+ -- Not working</h3>
<p>  Attempts have been made to get godot 4.4 games to convert but the new way of storage is whats messing me up. after 4.3 support, I will add 4.4 support</p>

<h2>Scripting</h2>
<h3>Godot 4.x</h3>
<p>  This is the easiest of the bunch and I'd say is pretty much complete. there are a few minor tweeks to be made, but it's so small you can fix it manually.</p>
