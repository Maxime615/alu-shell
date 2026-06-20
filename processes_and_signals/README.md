# Shell, Processes and Signals

This directory contains Bash scripts for managing Linux processes, PIDs, background tasks, and signal interception (`SIGINT`, `SIGTERM`, `SIGKILL`) under Ubuntu 20.04 LTS.

## Directory Structure

*   `0-what-is-my-pid`: Displays its own PID.
*   `1-list_your_processes`: Lists running processes in a user-oriented hierarchy (`ps auxf`).
*   `2-show_your_bash_pid`: Lists processes containing `bash` (Shellcheck `SC2009` disabled).
*   `3-show_your_bash_pid_made_easy`: Lists `bash` PIDs using `pgrep`.
*   `4-to_infinity_and_beyond`: Infinite loop printing "To infinity and beyond" every 2 seconds.
*   `5-dont_stop_me_now`: Kills the task 4 process using `kill`.
*   `6-stop_me_if_you_can`: Kills the task 4 process using `pkill`.
*   `7-highlander`: Resilient process that catches `SIGTERM` and prints "I am invincible!!!".
*   `67-stop_me_if_you_can`: Helper script to send `SIGTERM` to the highlander process.
*   `8-beheaded_process`: Force-kills the highlander process using `SIGKILL` (`-9`).
*   `10-process_and_pid_file`: Creates `/var/run/myscript.pid`, traps `SIGINT`/`SIGTERM` to clean up and print custom messages.
*   `manage_my_process`: Background daemon appending "I am alive!" to `/tmp/my_process`.
*   `11-manage_my_process`: Init script to control `manage_my_process` (`start`, `stop`, `restart`).
