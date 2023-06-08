
# JPMC Task 2 
Starter repo for task 2 of JPMC's Forage program
#
# BACKGROUND INFORMATION

Typically, traders monitor stock prices and trading strategies by having data
displayed visually on their screens in chart form. Often these charts will be
accompanied by alerts that notify users when certain events occur or when
preset price thresholds are hit.
JPMorgan Chase created the Perspective tool over many years to allow users to
present and manipulate data feeds visually in web applications.
Perspective provides a set of flexible data transforms, such as pivots, filters, and
aggregations. It utilizes bleeding-edge browser technology such as Web
Assembly and Apache Arrow and is unmatched in browser performance. It is
engineered for reliability and production-vetted on the JPMorgan Chase trading
floor. Now it’s available to the development community as an open source library.
If you want to explore that, a link is provided as an additional resource.
#
# TASK BRIEF

In this task you'll focus on the following:
1. Set up your local dev environment by downloading the necessary files, tools and
dependencies.
2. Fix the broken typescript files in repository to make the web application output
correctly
3. Generate a patch file of the changes you made.
4. Submit your work
#
# SET UP

Just like in the last task, you need to get your local development environment up and
running. Given that you completed task 1, you should already have python installed and
be familiar with git.
1. First, fork and clone the project repo: (Folder available in Task Resources folder)
○ Create a new virtual environment in the project root. Pycharm can do this
automatically for you using the “configure python interpreter” option in settings.
○ Install all project python dependencies. These are listed in the requirements.txt file.
2. In this task, we will be working with javascript in addition to python. Javascript has a
handy package manager called npm, which handles package tracking, discovery,
installation, and removal. We will be using it to install a series of javascript
dependencies to your machine. If you already have access to npm on your system, you
can skip this step. Otherwise, you will need to acquire it by following the instructions
here (npm comes bundled with nodejs):
https://nodejs.dev/en/learn/how-to-install-nodejs/
○ For this project to work, you must have node 18.10.0 installed on your machine.
Ensure you have the correct version by running “node -v” in your terminal. If you do
not, consider using nvm (https://github.com/nvm-sh/nvm) to install the correct
version for you.
3. Install the necessary dependencies by running `npm install` from the project repo
4. Start the python server by running server3.py from the project repo like so: python
datafeed/server3.py (note it’s important you run it from the root of the project repo)
5. Start the client by running `npm start` from the project repo

ADDITIONAL RESOURCES
1. How to Install Node.js - https://nodejs.dev/en/learn/how-to-install-nodejs/
2. JPMorgan Chase’s Perspective - https://jpmorganchase.github.io/perspective/
3. GitHub Page for Perspective - https://github.com/jpmorganchase/perspective/
#
