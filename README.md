# flask-implementation
LEARN MORE ABOUT FLASK IMPLICATIONS:
Flask is a web framework for Python, meaning that it provides functionality for building web applications, including managing HTTP requests and rendering templates. In this section, we will create a basic Flask application. In later sections, we’ll add to this application to create our API. Don’t worry if you don’t understand each individual line of code yet—explanations will be forthcoming once you have this initial version of the application working.

Why Flask?

Python has a number of web frameworks that can be used to create web apps and APIs. The most well-known is Django, a framework that has a set project structure and which includes many built-in tools. This can save time and effort for experienced programmers, but can be overwhelming. Flask applications tend to be written on a blank canvas, so to speak, and so are more suited to a contained application such as our prototype API.
Installing Python and Flasklink to this section
For this tutorial, you will need Python 3 and the Flask web framework. You’ll also require a web browser (such as Firefox) and a text editor (such as Notepad++ or BBEdit).

To download Python, follow this link, select the button that says Download Python 3.x.x, and then run the installer as you normally would to install applications on your operating system. The default settings should be fine.

To confirm that Python installed successfully, first open the command line. In macOS, click the spotlight icon on the top right corner of your desktop (the magnifying glass) and type terminal. The terminal should be the first application that appears. On Windows, click the Start menu icon and type cmd in the search box, then press Enter.

Once your command line is open, enter these commands:

python --version
pip --version
If the output for these commands includes a version number, Python is installed and available from the command line and you can proceed to the next step.

Next, you’ll need to install Flask. At the command line, type

pip install flask
This will install Flask using the pip package manager for Python. You should see some output ending in a notification that Flask has been installed successfully.

As an alternative to the above installation instructions, you can install the Python 3 version of Anaconda, which can be downloaded here. Anaconda comes with Flask, so if you go this route you will not need to install Flask using the pip package manager.

If you’re running into trouble installing Python, you may find this Programming Historian article on installing Python helpful. Note that the instructions in that tutorial are for installing Python 2—make sure you choose Python 3 when downloading installers from the Python website, since this tutorial uses Python 3.

If you don’t have a preferred text editor, I recommend BBEdit for macOS or Notepad++ for Windows.
