# BabblersRepo
A public repository for data and R scripts related to Arabian Babblers Research Project

Amiyaal Ilany Lab, Bar-ilan University, Ramat Gan, Israel: 
http://thehyrax.wixsite.com/ilanylab

Arabian Babblers Research Project:
https://www.zahavibabblers.com/

# GITHUB guidelines:
1. Keep your scripts in your personal scripts folder.
2. When working on group projects, move the script out of your personal folder to the relevant project folder, so that everyone can work on it.
3. Keep file paths short and sensible.
4. Upload your data on GitHub and use relative file paths - if the data are on your computer, and you have e.g. `data <- read.csv("C:/user/Documents/bird_abundance.csv")` in your code, only you will be able to read in that data since it's only on your computer. But if you load the data from the lab's repo, every member of the lab can use it, e.g. `data <- read.csv("data/bird_abundance.csv")`, where `data` is a folder within the lab's repo.
5. Always pull before you push in case someone has done any work since the last time you pulled - you wouldn't want anyone's work to get lost or to have to resolve many coding conflicts.

# Coding guidelines
1. Variable and function names should be lowercase.
2. Put short, explanatory comments after lines.
