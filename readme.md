# enomise-ville-ecolo

Let's learn how to make a simple website with some pictures and audio files. 

We will learn how to install a server so we can see our website as we are making it. 
Then, we will put the website onto GitHub, where it can be hosted for free.
We will make a QR code so that visitors to the model can see the website, read the information and listen to the audio recordings.

# Install a server 
This is for information only to learn about how the internet works. 
A server is a piece of software that sends and receives data so we can look at and use websites. 
Let's use The Apache HTTP Server, one of the most popular server softwares. 
Now make an index.html file and go to localhost in the web browser. 

# Edit the HTML file
Make the most basic with "Hello Ville Ecolo!"
Now make it funky by adding some template from w3 schools: 
https://www.w3schools.com/html/tryit.asp

# Recordings
* Record on iphone
* Send to computer
* Convert with FFMPEG from M4A to MP3
```
ffmpeg -v 5 -y -i m4a-sample.m4a -acodec libmp3lame -ac 2 -ab 192k mp3-bounce.mp3
```
* Increase volume as necesssary: 

```
ffmpeg -i input.mp3 -filter:a "volume=10" output.mp3
```

# Website

* The website files are put on github in the docs folder
* The website is located here: 

https://enomisiverson.github.io/ville-ecolo/


