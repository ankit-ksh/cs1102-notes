## ES Lab 2 Activities

### 2.1 Sleep Command Operations

- Launch the `sleep` command with durations of 1, 5, 100, and 1000 seconds.
  1. Send the `sleep` command to the background.
  2. Bring the `sleep` command to the foreground.
  3. List the PID of the `sleep` command.
  4. Run the `sleep` command in both the shell and subshells.
  5. Demonstrate the use of `pstree` command, `ps`, `ps -aux`.
  6. Schedule a `sleep` command at a predefined time, day, and date.
  7. Halt the `sleep` commands.
  8. Interrupt the `sleep` commands.
  9. Kill the `sleep` commands.

### 2.2 Use Cases of `cat` Command

- Find and display all use cases of the `cat` command.

### 2.3 Processing Access Log

- Use pipes, `wc`, `grep`, `uniq`, `sort`, `cut` commands to perform the following operations on an access log:
  1. Create a list of unique IP addresses present in the log.
  2. Print the total count of entries encountering a `404` error.
  3. Extract only the time data (`:00:11:33` from the example) from the log, keeping only hours and minutes.

### 2.4 Regular Expressions in Text Editors

- Using regular expressions in `vi/vim` and `Emacs`:
  1. Search for all appearances of "Macintosh".
  2. Search and replace the IP address, masking `83.97.73.245` with `83.xx.xx.245`.
