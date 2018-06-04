# movie-trailer-website
documentation 

Project Title: Movie Trailer Website

Getting started: 
	There are 3 files used for this project and being saved in the same folder MOVIE
1.	media.py :  The class Movie is defined
2.	entertainment.center.py: The class Movie is used
3.	fresh_tomatoes.py: HTML  tag stored in python file to display a website

•	The class named Movie have data and methods in it.
  Class Movie():

•	We can create multiple instances of a class .
Instances are the object of the class. In this project Name of the movie is the instances of the class. The instances used here are magadheera, bahubali2, bangalore_days, manam, rajarani, anandam.

•	Once we create a instances of a class constructor gets called is essentially __init__ method inside a class
__init__ : used to initialize all of the data associated with the instances or create space in memory for new instances.

•	The constructor uses the keyword self we consider self as itself or a instances in a question. When instances magadheera is created self is a magadheera.
  def __init__(self, movie_title, movie_storyline, poster_image, trailer_youtube):

•	All of the variable is associated with specific instances called instance variable.
              self.title = movie_title
              self.storyline = movie_storyline
              self.poster_image_url = poster_image
              self.trailer_youtube_url = trailer_youtube
print(bahubali2.storyline)

•	These are unique to an object and can be accessed using self keyword inside the class and instance name outside the class like 

•	All of the function inside the class that are associated with an instance and have first argument as self are called Instance Method.
    def show_trailer(self):

•	As a final output we get all our favorite Movie on the Webpage

•	To turn our code into movie webpage we need a code called fresh_tomatoes.py  and this python file has a function called 
    def open_movies_page

•	This function takes in a list of movies as input and as a output it creates and open a website that shows those movies that we gave in the entertainment.center.py

Prerequisites:
  To run our project we need to install python

INSTALLING:

If you are a window user:

1.	Download the Windows x86 MSI installer. If you're sure that your machine runs a 64-bit version of 
Windows, feel free to download the Windows x86-64 MSI installer instead.
2.	Once the download is finished, locate the file (it'll probably be in your Downloads directory) and run it. Note: the images below show Python 2.7.9, but the process is the same for newer versions.
3.	Follow the installation wizard. Let Python install to its default directory, C:\Python27\.
4.	Ensure that both pip is installed and that Python is added to your PATH.
5.	To confirm that your installation was successful, open IDLE, a program installed by Python that makes it easy to edit and run Python code.
a) Windows 7 (or earlier): Use the Start Menu to go to All Programs, then Python 2.7, and, finally, IDLE (Python GUI).
b) Windows 8: Search for IDLE. Currently, you can search by swiping from the right edge of the screen or by using the lower-right corner of your screen if you have a mouse.

If you are MAC user

1.	If you are using Mac OS X 10.6. If you are using 10.5, you will need an installer, 32-bit i386/PPC installer.
2.	Open the file that you downloaded. It should either be called python-2.7.12-macosx10.6.pkg or python-2.7.12-macosx10.5.pkg
3.	To confirm that your installation was successful, open IDLE, a program installed by Python that makes it easy to edit and run Python code.
a)	It should be in your Applications folder.
b)	You can also use Spotlight by pressing ⌘+Space and typing in "idle" to find it.
DEPLOYMENT:
•	In the webpage there is a list of 6 movies list with movie poster and movie name.
•	As we click on any Movie link in the webpage  we can see its trailer as a output.

BUILT WITH:

1. Google
One of the most popular search engines in the world has been built using Python. Python allows Google to switch the traffic and figure out the requirements of search.

2. YouTube
Python has been the driving force behind YouTube, a website used by millions for downloading and uploading videos of all hues and sizes.  The website has been coded in a way which makes it easier and extremely interactive for the user.

3. Quora
It’s a portal where you get your answers. You can post a question and you can get an answer from any part of the world.  Quora’s language programming has been developed using Python’s framework.

4. Dropbox
Many of our choices to store our data are going online. We create a document, we save it, and we share it. All of this is done online using Dropbox. It is an ideal way to preserve your documents online. This file hosting service has also been created using Python.

5. Yahoo!
Google’s biggest competitor in the search engine criteria. Yahoo and many of its subsidiaries, including Yahoo Maps, have been designed using Python.

6. Reddit
Reddit, popularly called internet’s front page has also been developed using Python. It is a place where you can find a lot of information and entertainment across thousands of categories. The website focuses on user-generated content. Many of the website’s features are dependent on Python for their functionality.

7. Instagram
 	Uploading and sharing photos has never been this exciting. Instagram has revolutionized the way pictures and videos are shared. The popular picture sharing website also relies heavily on Python for many of its functionalities, including the video sharing service.

8.  Spotify
Stream countless songs and music videos with Spotify. You just can’t get enough of your favorite musicians, singers, and composers. This popular website has also been created using Python. Spotify focuses on speed and Python complements that mindset really well.

9. Survey Monkey
When you think of conducting online surveys, Survey Monkey is the first name that comes to your mind. The cloud-based Software as a Service company founded by Ryan Finley in 1999 has also been created using Python.  The website, in its entirety, has been created using Python. It is easy to use and extremely interactive, all because of the Python.

10. Bitly
Bitly, the popular link management platform created by Peter Stern in 2008 shortens close to 600 million links annually. This website also owes greatly to Python as it came into existence because of Python.

VERSION:
Python 2.7.15 shell is the version used for this project.

LICENSE:
Since Python is a open source licenses grant permission to everyone to use, modify and run the program.
Python 2.7.15 license






