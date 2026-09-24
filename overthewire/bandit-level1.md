Objective: Find the password stored in a file called - and use it to log into the next room.

i got into a problem that the file wasnt opening with the cat command

turned out that - means an option flag so using ./ as a prefix of the file name force it to see it as a path not an option flag which make the command cat ./-
