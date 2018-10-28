# Launch quizme from bash in interactive mode

- executable R script that can launch [quizme](https://github.com/pchhina/quizme) from bash 
- since there is no direct way to force interactive mode in executable bash scripts, I use a workaround described [here](https://thesquareplanet.com/blog/interactive-r-scripts/). Thanks to Jon for this idea!
- script uses rclone for syncing database with google cloud storage (can be commented if not needed)
