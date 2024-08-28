# JPMC Task 1
Starter repo for task 1 of the JPMC software engineering program

# Task 1: Interface with a stock price data feed
##Set-Up
Before you can tackle any software development task, you need to set up your
development environment. You can think of your local development environment
as a virtual workbench with all the tools necessary to work on your project.
To set up your dev environment, follow these instructions:
-  Install python 3 to your system - any recent version of python 3 will
work fine, though the most up-to-date version is advisable. If you need help
with this step, check out this excellent guide from real python:
<code>https://realpython.com/installing-python/</code>
 
-  Fork and clone the starter repo here:
<code>https://github.com/theforage/forage-jpmc-swe-task-1</code>
    -  IMPORTANT! Uncheck the “Copy the main branch only” box in the fork
    dialog on GitHub. A model answer has been provided in a separate branch
    from main.
    -  if you are unfamiliar with forking, cloning, or git in general, take
    a look at the first two chapters of the git book here:
    <code>https://git-scm.com/book/en/v2</code>
 
-  Open the project in your IDE of choice - if you don’t have a favourite
python IDE yet, take a look at Pycharm Community Edition. It’s a
well-designed IDE by Jetbrains packed with features and plugins, powerful
enough to work on the most complex projects, and entirely free.
 
-  Create a new virtual environment in the project root. Pycharm can do this
automatically for you using the “configure python interpreter” option in
settings.
 
-  Install all project dependencies. These are listed in the
<code>requirements.txt</code> file.

# Notes
-   Used automation script for <code>dateutil</code> env import

# Task 1: Making changes
When you’re in a work environment, you’ll usually receive tasks in the form
of engineering tickets. Here is an example of what this task looks like in
the form of an engineering ticket

### Purpose
We want to process the data feed of stock A and stock B’s price to enable us
to analyse when trading for the stock should occur.

### Acceptance Criteria
getDataPoint function should return correct tuple of stock name, bid_price,
ask_price and price. Note: price of a stock = average of bid and ask
getRatio function should return the ratio of the two stock prices main
function should output correct stock info, prices and ratio
