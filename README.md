## Delete Discord message history
A simple shell script to automatically delete your message history on Discord.

### Getting started
These instructions will get you a copy of this project up and running on your local machine for usage, development or testing purposes.

1) Clone the repository or download and extract the ZIP files:  
  ```
  git clone <SSH or HTTPS>
  ```

2) Install the third-party software used in this project:  
* [xdotool](https://manpages.ubuntu.com/manpages/trusty/man1/xdotool.1.html) - A command-line X11 automation tool used to simulate keyboard and mouse inputs:  
  ```
  $ sudo apt install xdotool
  ```

3) Change the current working directory to your local copy of this repo:
  ```
  $ cd /path/to/local/repo
  ```

4) Execute the shell script and enter the number of messages you want to remove:
  ```
  $ ./delete_DM
  ```

5) When you finally activate a Discord window, **your messages** in the current channel will be removed.

### Tested with:
* Ubuntu 18.04
* xdotool 3.20160805.1

### Authors:
See the list of [contributors](https://github.com/MartijnCramer/discord_delete_msgs/contributors) who participated in this project.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

### Acknowledgments
A solution along the lines of [Craig Snyder](https://www.online-tech-tips.com/computer-tips/how-to-delete-your-dm-history-on-discord/).
