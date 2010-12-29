README
======

Qoobster is bash script written by me. It was created to automise downloading process from rapidshare. I wrote Qoobster to train programming in bash during SOP lessons.

HOW TO USE IT
-------------

Qoobster is bash script so don't forget to set executable flag.

Qoobster's params are links to rs files. You can add as many links as you like. 
./qoobster http://rapidshare.com/files/136423600/Welcome.to.the.NHK.2006.EP14.www.anime-download.go.pl.part1.rar If you want to put more than one link, type in console: ./qoobster http://rapidshare.com/files/136423600/Welcome.to.the.NHK.2006.EP14.www.anime-download.go.pl.part1.rar http://rapidshare.com/files/136430965/Welcome.to.the.NHK.2006.EP14.www.anime-download.go.pl.part2.rar 


If there are many links, you can put them all together in a file and launch Qoobster in this way:
(Caution: apostrophes used below are grave accent mark, they are on keyboard near tilde ~ ) 
./qoobster `cat file` 


If you want shut your computer down after downloading: sudo su
[ root password ]
./qoobster `cat file` && poweroff 

