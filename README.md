# Python Plot Strava Data
Create plots of Strava data using Python and Jupyter notebook.

This code produces a graph showing the routes of all your Strava activities. The user can filter which activities are included in the plot.



## Contact Details ##

Michael Kirker

* Email: michael@michaelkirker.net
* Website: [michaelkirker.net](http://michaelkirker.net)
* Git repository for this project: [https://github.com/michaelkirker/PythonPlotStravaData](https://github.com/michaelkirker/PythonPlotStravaData)



## Example output

The following is the most recent output from running the Jupyter notebook

![Example](.\output\my_activities.png)



## Get your Strava data

While Strava has an API to access your information, I have had some issues with the authentication process. Therefore, this code is set up to operate without the API. 

Therefore, you need to export your Strava data to the `stava_input` folder of this repository.

Steps to export your Strava data:

* On the Strava website select `my profile`.
* From the menu select `My Account`.
* Under `Download or Delete Your Account` click on the `Get Started` button.
* Under Step 2, click on the `Request Your Archive` button. Strava will then send you an email once all your data is ready to download. You can now close the website and wait for Strava to email you that your data is ready (it should only take a few minutes).

When you have received the email from Strava, download the archive of your data from the email, and unzip it into the `strava_input` folder of this directory.



## How to run this code

1. Download you Strava data (se instructions above), unzip the file and store the content in the `strava_input` folder.
2. In the Jupyter notebook `PythonPlotStravaData.ipynb` adjust the setting in the cell related to `Define user settings`
3. Run the notebook
4. Output is saved to the `./output/` folder.



## Current limitations of the code

Things to fix or improve in the code over time:

* Code only handles .gpx files at the moment
* Currently the subplots have a white background when displayed in the notebook, but have a correct black background in the saved image file. Correct the displayed figure in the notebook



## Inspiration

This code was inspired by the following youtube clip [https://www.youtube.com/watch?v=7TBjtLG-lpM](https://www.youtube.com/watch?v=7TBjtLG-lpM) by Andy Cotgreave and Ken Flerlage.

