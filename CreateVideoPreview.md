```
13

I like using an easy to use unix command line bash script called VCS - Video Contact Sheet. Their official page: http://p.outlyer.net/vcs/

Its a lot easier to use even easier than a GUI

''It is a bash script meant to create video contact sheets (previews) aka thumbnails or previews of videos. Any video supported by mplayer and ffmpeg can be used by this script. '' You will need to have either ffmpeg or mplayer installed on your system.

Usage:

vcs input-filename -U0 -i 1m -c 3 -H 200 -a 300/200 -o save-filename.jpg

How the command works

Edit input-filname to the name of your video file!

    -U0 (no name in footer - or else it displays the host name - note this is zero not the letter O)

    -i 1m (sets the capture time interval in mins - in this case it's every minute - you could also use -n instead which sets the number of captures for example -n 21 will create 21 images, but don't use both)

    -c sets number of columns (here it's 3 columns)

    -H 200 -a 300/200 (sets size and aspect so file is not too big - seems you have to do both)

    -o filename.jpg (use .jpg as the default as .png is too big - and change the filename to one of your choice !)


```
