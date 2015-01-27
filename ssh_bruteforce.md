I downloaded a file of the 10,000 most common passwords and saved it as 10kmc.txt. 
I then went to the command line and ran medusa -h mthack.me -u test -P ./Desktop/10kmc.txt -M ssh.

[Imgur](http://i.imgur.com/TqxTerf.png)


The script ran until it found the password, changeme. I then ran ssh test@mthack.me and entered the password changeme.


[Imgur](http://i.imgur.com/dQZc9dH.png)


Access to log into mthack.me was denied and the sha1sum was displayed in the dialogue which I then copied to the subimssion fourm.

[Imgur](http://i.imgur.com/U3hTKBC.png)
