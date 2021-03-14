Zach Serotte, Maclee Machado, Muzammil Mahmud

1.) When we were adding the -l functionallity for the ls command we were opening files and forgot to close them. This gave us an error
whene we tried to call the ls -l function twice, as it tried to open a file that was already open
2.) When doing the cp command, we forgot to set the parent of the new the file that we are cloning to be a nullptr
3.) When doing the cp command, we forgot to add the name of the file that we were making when calling the addfile function. For
example, we were trying to copy the file you.txt to the directory root/dir. Our program kept throwing an error saying that the file
that we wanted to make already exists. To fix this we changed the string that we passed into the addFile function to
root/dir/you.txt
