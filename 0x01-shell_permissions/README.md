#Task 0: 0. My name is Betty
Create a script that switches the current user to the user betty.
You can assume that the user betty will exist when we will run your script
#Task 1:Who am I
Write a script that prints the effective username of the current user
#Task 2:Groups listing where the current user is part of (groups)
print all groups a user belongs to using commang groups
#Task 3: New owner
Script that change the owner of the file hello to the user betty
chowner betty hello
#Task 4: Create an empty file hello
Write a script that creates an empty file called hello
#Task 5:Add execurte permission to the current user
write a script that adds permission to the owner of the file helo.
#Task 6:Multiple permissions
A script that adds multple permissionsto the owner and the group owner, and read permission to the other users, to the file named hello
#Task 7:add execution permission to all Everybody!
a script that adds execution permission to the owner, the group owner and the other users, to the file hell
#Task 8:james Bond
set permission as follows to the file hello Owner: no permission at all Group: no permission at all Other users: all the permission (007)
#Task 9:John Doe
Write a script that sets the mode of the file hello to this:-rwxr-x-wx 1

#Task 10:Look in the mirror
Write a script that sets the mode of the file hello the same as olleh’s mode.
#Task 11:
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
#Task 12: More directories
Create a script that creates a directory called my_dir with permissions 751 in the working directory (mkdir -m 751 my_dir

#Task 13:Change group
Write a script that changes the group owner to school for the file hello (chown -hR vincen:staff .)
#Task 14
Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.(chown -h vincent:staff _hello)	

#Task 15:Symbolic links
Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.(chown -h vincent:staff _hello)
#Task 16: If only
Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume (chown --from=guillaume betty hello)


#Task 17:Star Wars
Write a script that will play the StarWars IV episode in the terminal. (telnet towel.blinkenlights.nl))
