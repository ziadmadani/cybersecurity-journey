Objective: The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties: owned by user bandit7, owned by group bandit6, 33 bytes in size

the room was a good practice with the find command i first used the ls and du to find any clue without any progress i find out that the find command could find find by user or group using this commands
find . -user X for owner / find . -group X for groups we coudl add -ls to show details
after hoping for finding the file it didnt find it, but replacing the . with / let me search from root which allowed to get to the file immedatly using cat
