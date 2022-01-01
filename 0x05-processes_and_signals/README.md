# 0x03. Shell, init files, variables and expansions

## About this Directoy

This directory contains programs that demonstrate make use of the following linux commands.

1. ps <br>
2. pgrep <br>
3. pkill <br>
4. kill <br>
5. exit <br>
6. trap <br>

## Programs in this Directory

Program Name | Program Description | How to Run Program
------------ | ------------------- | ------------------
[0-what-is-my-pid](./0-what-is-my-pid) | script that displays its own PID | ./0-what-is-my-pid
[1-list_your_processes](./1-list_your_processes) | displays a list of currently running processes | ./1-list_your_processes
[2-show_your_bash_pid](./2-show_your_bash_pid) | displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process | ./2-show_your_bash_pid
[3-show_your_bash_pid_made_easy](./3-show_your_bash_pid_made_easy) | displays the PID, along with the process name, of processes whose name contain the word bash | ./3-show_your_bash_pid_made_easy
[4-to_infinity_and_beyond](./4-to_infinity_and_beyond) | displays To infinity and beyond every after 2 seconds indefinitely | ./4-to_infinity_and_beyond
[5-dont_stop_me_now ](./5-dont_stop_me_now ) | stops 4-to_infinity_and_beyond process | ./5-dont_stop_me_now 
[6-stop_me_if_you_can](./6-stop_me_if_you_can) | script that stops 4-to_infinity_and_beyond process | ./6-stop_me_if_you_can
[7-highlander](./7-highlander) | displays To infinity and beyond indefinitely, With a sleep 2 in between each iteration, I am invincible!!! when receiving a SIGTERM signal | ./7-highlander
[8-beheaded_process](./8-beheaded_process) | script that kills the process 7-highlander | ./8-beheaded_process
