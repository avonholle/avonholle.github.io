To edit and preview the minimal mistakes web site I have created for my graduate work do the following (on my Windows 10 machine):

1. Go into command prompt as an administrator
	* click on magnifying glass at bottom left and type cmd.
	* right click on 'command prompt' and run as administrator
	* type 'bash' and that should get you into the Linux ubuntu environment so you can run jekyll.
	* go to the directory that has this web page (and this readme.txt file).
		* type 'jekyll serve' and you should get the web page up and running locally for checks.


---

Track list of changes to web page, 2018-04-25

1. changed font size of main page. 
	* Went to /_sass/minimal-mistakes/_page.scss
	* changed   

p, li, dl {
    font-size: 1em;
  }

to

p, li, dl {
    font-size: 0.975em;
  }

2. 
