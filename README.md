# Money Ball

In the movie / book [Moneyball](http://www.imdb.com/title/tt1210166/) - data analysis
is employed to discover that teams that had a roster containing players with a high
on base percentage (OBP) did very well in the regular season. Using this knowledge
the General Manager was able to create a very successful team on a shoestring budget
with players that had a high OBP.

First get the most recent complete baseball statistics dataset from [Sean Lahman's website](http://www.seanlahman.com/baseball-archive/statistics/). Unzip it into a `data/` directory inside your repository.

This notebook puts together the starting 9 player roster for a single season.  How?
You need to find the players with the highest OBP and the lowest salary in any specific year. Make
sure you are removing outliers (an OBP of 1.0 is not an indicator of a perfect player, more like
they possibly only played 4 or 5 games and had good luck, alternatively an OBP of 0 is pretty
bad).  Your 9 player roster should include:

 - (1st, 2nd, 3rd) Baseman
 - (Left, Center, Right) Fielders
 - Short Stop
 - Pitcher
 - Catcher

A player that historically played multiple positions can not account for 2 places on your roster.

### To View This Notebook
Just click on the `moneyball.ipynb` file above.

### To Run This Notebook
#### System Requirements / Installation

* You will need to have **python&nbsp;3** installed on your machine. See [python's site](https://www.python.org/) for details.

* Clone this repo onto your machine.

* You will need to make sure that you have a virtual environment running in the folder that you intend to work from. [See this site for details if you're not familiar.](http://docs.python-guide.org/en/latest/dev/virtualenvs/) **Complete this step before attempting the below.**

* In your command-line program (such as Terminal on Mac&nbsp;OS&nbsp;X), navigate into the newly created repo. By default, this will be called `moneyball`. Install the requirements file by runnning **`pip install -r requirements.txt`**.

#### Opening the Notebook
* Using a command-line program, navigate to the folder containing the downloaded file and run the following line: **`ipython notebook moneyball.ipynb`**

* **Note:** This will open in a browser window and take over the command-line program's window until you close out of IPython Notebook. If you have closed your browser window, but your command line is still running the notebook, kill the process by pressing `Ctrl+C` or quitting the program entirely.

<!--
## Hard Mode

In addition to the required objectives outlined above you should adjust each player's salary
for inflation based on the year they earned the salary.

Also you are required to put together an "all time best" legacy team based on their adjusted salary. -->

#### Note

You will have to calculate the on base percentage for each player.  Here is the formula you
might want to use [On Base Percentage](https://en.wikipedia.org/wiki/On-base_percentage)
