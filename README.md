# About
A small program that helps batch download files on the internet by simply feeding the url of the parent page to the command line.

# Motivation
Finding all slides listed on a webpage waiting to be downloaded, I figured creating a little tool would be helpful in saving time and energy. So I took some time to implement this small gadget.<br>

# How to run
1. Download FileDownloader.py to your local machine.
1. Open terminal under the folder where FileDownloader.py is.
2. Type the following command in terminal and hit enter: "python3 FileDownloader.py".
3. Follow the directions of the program (basically just provide the url that leads to the list of files, and download will immediately start).

# Potential error and fix
**Error Code**: "ModuleNotFoundError: No module named 'bs4'":<br>
**Fix**: Simply copy and paste "pip install BeautifulSoup4" to your terminal, hit enter and re-run "python3 FileDownloader.py".<br>

# Note
1. This program currently only supports downloading pdf and ppt files (support for other formats may be added later).
2. For bug-free experiences, preferably your files are supposed to be in situations like this:
<img width="458" alt="webpage demo" src="https://github.com/pppiyo/File_Downloader/blob/master/webpage%20demo.png">

  That is to say, 1) you have a parent link which leads you to see a page like this; 2) each file has its own link provided.<br><br>
3. Outcome will be like the following. You should be able to find the files in the folder where FileDownloader.py is.<br>
<img width="916" alt="webpage demo" src="https://github.com/pppiyo/File_Downloader/blob/master/code%20effect.png">
