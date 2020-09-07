# Instructions to use this repository with syzygy

## If first cloning into syzygy:

1. Go to https://utoronto.syzygy.ca, log in with your UTorID, and start the server.
2. Near the top-right-hand corner of the home menu, hit the drop-down menu "New", and click on Terminal.
3. in the terminal, create a PHY407 (or whatever) folder and go there:

  `mkdir PHY407`

  `cd PHY407`

4. In there, clone the repo of my lectures:

  `git clone https://github.com/PHY407-UofT/Lectures-2020.git`

  This should create a new folder called `Lectures-2020`, in which my lecture notes will be located.

## Refreshing the lecture notes

At the beginning of the term, you have (had) my notes of 2018. As the class progresses, I will of course add or modify them, correct typos, etc.

5. To get the latest updates, start by repeating steps 1-3 above.
6. If you just want to play around with the notes a little in-between two updates but want your repository to closely match what I have on GitHub, enter the command 

  `git fetch --all`
  `git reset --hard origin/master`

  in the Terminal, where you left at the end of step 5, whenever you want to re-align your notes with mine.

7. If you want to be more fancy, modify the notebooks significantly and keep your modifications while keeping up-to-date with my content, I suggest you create your own "fork" and work on it. You can then sync your fork with my repository by following these instructions: https://help.github.com/en/articles/syncing-a-fork

## Opening a Jupyter notebook:

8. Repeat steps 1-3 above.
9. Repeat step 6 or 7 above, probably.
10. You can navigate to the Jupyter file, using the graphical interface of the home menu of syzygy. You are looking for a `.ipynb` file.
