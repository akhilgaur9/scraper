#   This is a Soundcloud scraper built in python.

The Chrome web driver is needed from selenium which is a portable framework for web applications.
It can be installed using pip install selenium frm command prompt or conda install selenium if one is working in Anaconda.
Then the chrome web driver executable file is downloaded from the website and saved in the path.
requests library is installed using pip install requests. It is a python HTTP library and makes HTTP requests simpler.
bs4 library is installed using pip install bs4.It is a python library for pulling data out of HTML or XML files.
The urls for top songs,new songs,artists,mix are defined for soundcloud.com.
A user input menu is built where user can search for a track,artists,top charts,new and hot charts.
The user can also access the tp 50 tracks for a given genre which can be done using the BeautifulSoup4 library using the requests library to pull off the required details from the soundcloud url.
The genres can be pulled from the  "a" tags of the HTML
The top 50 songs for each genre can be pulled form the soundcloud site.
