0-what-is-my-pid

A Bash script for displaying its own process ID (PID).

1-list_your_processes

A Bash script for listing all currently running processes for all users,
showing process hierarchy in a user-oriented format, including processes without a TTY.

2-show_your_bash_pid

A Bash script for displaying lines containing the word bash in order to identify the PID of the current Bash process, without using pgrep.

3-show_your_bash_pid_made_easy

A Bash script for printing the PID and process name of all processes whose name contains bash, without using ps.

4-to_infinity_and_beyond

A Bash script for printing “To infinity and beyond” indefinitely, with a 2-second pause between each iteration.

5-dont_stop_me_now

A Bash script for stopping the 4-to_infinity_and_beyond process using kill.

6-stop_me_if_you_can

A Bash script for stopping the 4-to_infinity_and_beyond process without using kill or killall.

7-highlander

A Bash script for:

Printing “To infinity and beyond” indefinitely

Sleeping 2 seconds between iterations

Displaying “I am invincible!!!” when receiving SIGTERM

67-stop_me_if_you_can

A Bash script for stopping the 7-highlander process (adapted from 6-stop_me_if_you_can).

8-beheaded_process

A Bash script for killing the 7-highlander process.

10-process_and_pid_file

A Bash script for:

Creating /var/run/myscript.pid containing its PID

Running indefinitely

Handling signals with custom messages

Cleaning up the PID file before terminating

manage_my_process

A Bash script for running a background daemon that repeatedly writes
“I am alive!” to /tmp/my_process every 2 seconds.

11-manage_my_process

A Bash init-style script for starting, stopping, and restarting manage_my_process,
while managing its PID file in /var/run/my_process.pid.
