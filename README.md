# Data-Moshing Videos is Super Easy! (?)

Data Moshing apparently means dropping p-frames and glitching the f out of them. It's rad.

It's pretty easy to do in the command line!



just convert any video to an avi like this:
ffmpeg -i input.mp4 output.avi

then you can just f-up the videe from the command line like this:
datamosh output.avi -o moshed-output.avi

then invert the video cause why not?
ffmpeg -i moshed-output.avi -vf negate inverted-output.avi

and boom, you got an f-ed up video



to get the datamosh utility working refer to this repo
https://superuser.com/questions/1336315/invert-colors-of-a-video-using-ffmpeg

or jsut run this, which might work?
gem install aviglitch

maybe try cloning the repo and running
bundle install

that might work too
