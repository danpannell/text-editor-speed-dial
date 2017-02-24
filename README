This README only contains information already in the script.

# SPEED EDIT  
#   The idea is to speed up development of shell scripts or writing by making it quick and easy to open a document no matter
#     what current directory you are using.  This command may also be useful in windowed desktops that give access to the commandline
#     such as an Xwindows based desktop. (Unity is an example).  
#
# -- currently set up to use vim and wordgrinder
# -- SPEED EDIT places four useful functions into a bash environment.
#
# speditset() sets a my_SPEDITFILE file variable into the environment as the currently edited filename.
#   This should be the file that is frequently edited with a text editor, such as a script that you are working on sporadically
#   or a personal journal.  
#
# After sourcing the spedit file, type: speditset [ PATH to file ]
#   For the rest of the session typing 'spedit' <ENTER> will open that file in an editor.
#
# In addition unlimited speed dials can be set up by typing: speditset [ Path to file ] [key]
#   A dictionary of keys with matching file paths is stored in an environment variable.
#   For the rest of the session typing 'spedit' [key] <ENTER> will open the associated file in a text editor.
#
# There are two additional commands: speditwords and wedit
#   typing 'speditwords' <ENTER>  lists a short summary of all spedit related commands
#
#   People who do not use wordgrinder may simply ignore the wedit command.  It converts the text file to wordgrinder format, opens
#     wordgrinder, and then after a successful save and close converts the resulting wordgrinder file back to text.  It is a little
#     risky, since if wordgrinder fails the text file may be ruined.
#
#   typeing 'wedit' [ key ] <ENTER> opens a text file in word grinder instead of a text editor and handles conversion in the background.
#     wordgrinder does not use text files.  Currently both the wordgrinder file and the text file will be kept, however only the
#     text file should be used with the speditset command, and there is no matching weditset command.  Only the text file should be
#     considered worthy of archiving, either; as wordgrinder may prove unstable compared with a simply text editor.  Backups are
#     a good idea in case something goes wrong, and sometimes things do go wrong.
#
