# myi3pystatus
![Screenshots](https://github.com/zakariakov/myi3pystatus/blob/master/screen.png)

**i3pystatus

https://github.com/enkore/i3pystatus

**fonts

https://github.com/FortAwesome/Font-Awesome

https://github.com/powerline/fonts

 **config
 
Copy this file i3pystatus.conf to your home folder under ~/.config/i3/i3pystatus.conf

edit i3 config ~/.config/i3/config

replace this line status_command i3status

::

bar {

  font pango:Inconsolata-dz for Powerline  10
  
     #status_command i3status
  
  status_command    python ~/.config/i3/i3pystatus.conf
  
  	}
  
  
