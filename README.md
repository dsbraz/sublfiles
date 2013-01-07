<h1>Sublime Text 2</h1>

Clone the repo to ~/.subl<br />
cd ~/Library/Preferences<br />
rm com.sublimetext.2.plist<br />
ln -s ~/.subl/Preferences/com.sublimetext.2.plist<br />
cd ~/Library/Application\ Support/Sublime\ Text\ 2<br />
rm -rf *<br />
ln -s ~/.subl/Application\ Support/*<br />
