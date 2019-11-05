# Lyrics
lyrics is a simple bash script I built for myself to fetch lyrics of the song on the linux terminal. 

I love listening to music and I always keep forgetting the lyrics. Most of the time I keep singing randomly so I made this to see what I'm singing to. Follow the easy instructions.

# Steps

1. Clone/Download this project.
2. Go inside this project(in lyrics folder).
> cd lyrics
3. Copy paste this command.
> sudo ln -s $(readlink -f lyrics) /usr/bin/lyrics
4. Done.

P.S. Make sure you have the correct permissions to run the script. See example


#### Usage: lyrics [Artist Name] [Song Title] ####

#### Example: Get lyrics of New York by Frank Sinatra ####
> lyrics "Frank Sinatra" "New York"

#### Example: Also works the other way around ####
> lyrics "New York" "Frank Sinatra"

#### Note: This does not work for artist name or song title with special characters. ####
