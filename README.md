# Working Scripts
## A collection of scripts for making work better

### Pomodoro
 Make sure you have executable permissions and `notify-send` works on your computer
- `-t` will set the pomodoro time (in minutes)
- `-c` will set the number of pomodoro iterations
- `-b` will set the break time (in minutes)
- `-h` will give you a help message and exit

To start in the background run `./pomodoro [OPTIONS] &` and you can see the background stuff with `jobs`
NOTE: killing the terminal that you start these in will also kill the background jobs
