
Your space ship enters an asteroid belt, try to avoid 
collisions!

wxAsteroids is a game demonstrating the wxHaskell GUI.

To run the game, you will need wxHaskell, see:
  http://www.haskell.org/haskellwiki/WxHaskell/Download

If wxHaskell is installed, and you have cabal-install 
on your system, give the folllowing command to install 
wxAsteroids:
  cabal install wxAsteroids

Another option is, to download the wxAsteroids tarball 
from Hackage:
  http://hackage.haskell.org/cgi-bin/hackage-scripts/package/wxAsteroids 
and unpack it; go to the directory with the game code 
and enter the commands: 
  runhaskell Setup configure
  runhaskell Setup build
  runhaskell Setup install

You will get a message about the directory in which the 
executable is installed; this directory must be in the 
search path. 

Give the following command to start the game:
  wxAsteroids

Use the left and right cursor keys to move the ship sideways. 
Ctrl-n creates a new window with a new Asteroids game. 
Ctrl-p pauses/resumes the game. 
To increase the speed of the space ship, press '+'; 
to slow down, press '-'.

For a detailed description of wxHaskell and the program, see:
"wxHaskell, A Portable and Concise GUI Library for Haskell"
  http://legacy.cs.uu.nl/daan/download/papers/wxhaskell.pdf

Further information about wxHaskell can be found at:
  http://www.haskell.org/haskellwiki/WxHaskell

