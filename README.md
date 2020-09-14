# sway
![Alt text](screenshot.png?raw=true "Title")
<!-- ![Alt text](screenshot_alt.png?raw=true "Title") -->


<h5>Optionnal but recommended</h5>
<ul>
	<li>waybar</li>
	<li>azote</li>
	<li>kdeconnect</li>
	<li>wofi</li>
	<li><a href="https://aur.archlinux.org/packages/rofi-lbonn-wayland-git/">rofi</a></li>
	<li>brightnessctl</li>
	<li>grim</li>
	<li>slurp</li>
	<li>swappy</li>
  <li>swaylock-effects</li>
	<li>oguri (for dynamic wallpaper)</li>
	<li>nwg-launchers</li>
	<li><a href="https://github.com/adi1090x/dynamic-wallpaper">dynamic wallpapers</a></li>
	<li>font awesome (i noticed it a bit to late)</li>
</ul>
<h5>Install config files</h5>
The script is written for pacman. If you use another package manager simply delete line 14 to 17 and add 'pkgmanager "$1"' below the if statement.
<ol>
	<li>git clone https://github.com/snakedye/sway_config.git</li>
	<li>chmod +x install.sh</li>
	<li>./install.sh</li>
</ol> 
<h5>For Arc Theme, install sass and run theses command in the arc-dark directory:</h5> 
<ol>
    <li>./autogen.sh --prefix=/usr --disable-gnome-shell --disable-cinnamon --disable-plank --disable-unity --disable-xfwm</li>
    <li>sudo make install</li>
</ol>
<h5>If you have Qt apps that aren't displayed in the desired theme</h5>
<ol>
	<li>Install qt5ct</li>
	<li>Go in /etc/environment</li>
	<li>Add QT_QPA_PLATFORMTHEME=qt5ct and save</li>
	<li>Refresh sway (ctrl+Shift+C)</li>
</ol>
