# Myrm
# Usage
		./myrm file1 file2 file3 -l -L -g file1 file2 -p

# Purpose		
    Move the files to a trashroom first insteadong of  a file immediately
		it use a function to check if the argument is a argument option or file
# Options
		then use case staement for different options
		since -g can have arguments after it, there is a while loop in the -g case,
		it treats all the files after -g and before another command options as the files input 
		for -g
 		-t take out the trash 
 		-l List the files in trashroom
		-L List the files in trashroom with detail
 		-p pick through the trash, enter r to recover the file
			to the current directory
			enter t to remove the file from trashroom
		-g get back the files followed by -g option
 			for example:myrm f1 f2 -g f3 f4
				f1 f2 is moved to trashroom and 
				f3 f4 is recoverd from trashroom	
