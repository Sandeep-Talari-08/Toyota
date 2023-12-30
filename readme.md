Git init - initialise a empty git repository


Git add . - adds all the files to the staging


Git commit -m “message you want to convey to commit this changes” - this command is used to commit the changes

Git status- used to check the status of the project like what are the changes that are made on this project. Green shows the files that are committed and red shows that the files are not committed

Touch name.files extension — this is used to create the new file inside the repository

Cat filename.ext — it displays the data inside the file

Git log— show all the recent commits and changes made by the people 

Git reset change ID. - this will delete all the commits which are committed after the selected ID and restores to the older version which is the version of the id that ie mentioned here


Vi file.ext— this command is used to write something inside the files after executing this command line, you have to press ‘I’ to insert some data. After inserting you have to press escape and then type :x which will get you out of the file

Rm -rf filename      - this will remove the file


If you have made few changes to the project but you don’t want that changes to be committed no the changes should be in your current working directory, you can simply say Git stash- this will make all the changes that you’ve made after the last commit into a separate dir 

Below is the example message -“Saved working directory and index state WIP on main: e77797d i've created a new text document for storing the objects”

Git stash clear- will clear all the stash data
