# Bane
Generate Baneposts quickly and easily from the command line.

[This project](https://blog.ctis.me/banepost-c-easy-baneposting-for-the-linux-enthusiast-5742dc6ccdfa) originally started as a small Gist, but has since been moved to its own repository.

## Installing Bane with Homebrew

```
brew tap ctrezevant/bane https://github.com/ctrezevant/bane.git && brew install bane
```

## Compiling from Source

_Installing and using Bane is a simple matter of_:

###### Step one: Clone the repo
```
git clone https://github.com/ctrezevant/bane.git && cd ./bane/
```

###### Step two: Build Bane
```
make && make install
```

###### Step three: Run it!
```
Charltons-MacBook-Pro:testbane charlton$ bane

.........................,::,,,~~+==+++=+++=====................................
.......................:.,:~~:::,:~~~~~++++=~==~I,..............................
......................,,~7I?III:=::~=~~~=++~:~,:~II~............................
......................=77III??III~,,~=~=++++==+=~IIII,..........................
....................=IIIIIIIII7II?~,~:=~===+==:::IIIIII.........................
...................77IIIIIII???7III~:~=~=+====~~~?IIIIII........................
..................IIIII??+II7???I??I~::=======:::=IIIIIII,......................
.................III??I?????I????=?II=,=::~:::::::IIIIIIII,.....................
................:????II??+?+++?+=?+?I?.,:::~:~:~::?IIIIIIII.....................
................?I????I???+IIIII+III77:,::~:,~~~::+??IIIIIII....................
................?+???I???++??I?I??7I77I=,.,,,..~:.=?I?IIIIII,...................
................I?+???I??+++???I?II7I?7+=~::~=~=~=+I??????II?:..................
...............=?+???????????IIIII??+?II~:,~~~:=~?+I7IIIIIII7I7II,..............
..............:+??+??????????II7777777??7~.~=::,,=I7I?+===?III7777 7I?=?~.......
............,+I++?+I?I??I????IIII??I7777+~,=~~+++?7::,:~=+=?7I??I?77777I+?,.....
.........:?7II+++??????????????+~::,~~::~~=++?:~~I=:,,,,:~+=I7~~====II?777 7?,..
.....+I77777I+==+??I???I???I+~~~===~~:,,::=+??=~??:~~:~~,,:~+7+~~=+=?????I7I777
..,+I7?I+??I?+::=+?I????I??+~~~:,~:,:,~,~~:~~::::~=~====?I=~=??~====+?+++==++I77
I7I7II?+===~=:..+=?I?I?????+=:::=?====~~==~==+==++=+++++I77???I:~=~=++===??+?++=
777??+===~~:~:~=,=??????I???+=+?++==~=++?~====++=++===+=I7IIIII~~~=+=++==?=+++++
77I+I?++===~:=+I7:I?I?????IIIII?III??I7~?==+?:~,::~+=,.,,77I?II~:~~~=?+++??+???+
7IIII+??=+==~:,7..~I???????I777777I77~:~+.:..,?77:= 7:77., I?I?~:~~==?++++=++I??
III+=+==?++=~~,.:~=:~+++?II??I7I77II=?...,:77=:77+. I++?7I77II7::::~~===+?+=+???
??I?I+?++?===~:,::~=.:~+?????III77I+?7:,+++7I.:I7+.7II,+7~++7I:~~~~~~~=++++I+?=+
II=+??++?=+=~~~,:~~:~?,,=+?=???III+I7+?+,.=77.,?77.+? .+I7=+?I,+~~===~==?++??+++
?III?III??+=~~:,:~~~:::+..,~+?++++=7I+++..:77..:I?..??.~==+++7?=~~~~~~===+++++=+
7IIIII++?+++~::,:~~~~~:::~:,.,~~==+7+??+..:?I=.+I=.,=+.~~~~=+I7,::~~~==++=++++??
I??+?I+??+=+=:,:::~=++=:~::,,~,.,,77=??,..,:~~:~~=,~?I:~:=.++?I7~~:~++=====++++?
I??7?++?=++=~,:,,:~~?????+~:::,,,+7.=I?...:.~~~,+=..:,,+,,==??I,7~======+++=++++
?IIIIII???++~::::,:~++????==++:::7 .+7?+,....~:~:....:~?+~+++=..~=~~~==++=++=+++
II???????I++=~::,+,~~+????==77+.~7:.+?II?I~:===.~~:,~~.=I7?.?.+,==~~~~~~+=+??++?
IIII?I?++?++=~::~~.:~~==???=7777II...,+?~~:I7I:.??=:77+.=777+::,=~~~~=~~++++=++?
I+?I?I=I?++++=~::::,:~~~==+++777?.I+.,,..., 77..+I=.=77~,,??7,+:++==~~~+===+=+++
??==I?+++?+++=~::::,,,~~~~:~=~,?I,,=:.,=,,I7I:..777.,77 :=~+?I==+++=~=~~====+??+
7I77I7II?++====::::,,:,,~~~::::=..~.,.~~:,??I...7 7,.?77:+.+I7:~===+===~++++?+++
I77?+III?++?++=:::::,,,=:.~:::,,,:::,.~+?,?+?,,,??+:,+77~+,?II7+==~~==~=~++==+?=
III?II?+++=+==++:::::,:+??=.,::,:::,:+77==II?:~,II~:,:I7,..?I++7?~==~=~~~:~~~=??
7I=I?++??===+++~:::~::,=?III+..,,,,,,77?:.7I?,:.,,:+=.,,:.++I+??+===++=~::+:~=++
I????++??+=?+=+:::::::,~??I???+:,.,:77+.,.I?++,~,,:~~,.~~~.?.?I?++++==~==~=~~:?+
777+II?+?=?++=+=:::::::=+?????+++~:~+?,..,~++,,::::::::,,~+++??~:..,,..,~~===+~=
?7I=====+??I?++=::~:::==++??++++++=+??,..:~,:,:,,,:,,,,,.,=II+,.,,++::,...,77777
 77I====+7I++7+?::,:~===++?+++??+++++~~~=,,,,.,,,:::=++++???I?+:.,.:~:~:,..77777
+=I?+++????+=~+~:::~=++++=+++??????+?=====~~======++++++????I?=~,,,.,...,,.?7777
                    Speak of the devil and he shall appear.      
```


Enjoy!
