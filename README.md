# firemenu

firemenu presents a list of applications to the user 
and starts the selected application in a firejail sandbox.

You can regenerate and edit the list by pressing the Edit button in firemenu.

If firemenu can't find your graphical editor, or if you prefer a different one, 
you can set the other_editor variable in the head of the script:
  /usr/bin/firemenu

It's also possible to edit the list directly in ~/.config/firemenu.list 
Just comment out the apps you don't want to show in the menu. 

Note: Adding apps to the list will only work if there is a firejail profile
for that app. Firemenu reads the list of .profile files in /etc/firejail to
determine which apps are eligible.

Note 2: This program does not have its own icon. Maybe it should. 


fsmithred@gmail.com

License: GPL-3

On Debian systems, the complete text of the GNU General Public License
can be found in the directory "/usr/share/common-licenses"

