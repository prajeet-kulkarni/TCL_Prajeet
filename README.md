# TCL_Prajeet
## Day 1
'''
#!/bin/tcsh -f
echo " This is a TCL file created by prajeet "

set my_work_dir = `pwd`

#------------------------------------------------------------------------
#---------------------------TOOL INITIALIZATION--------------------------
#------------------------------------------------------------------------


if ($#argv != 1) then
	echo " Info: Please provide a csv file "
	exit 1
endif

if (! -f $argv[1] || $argv[1] == "-help")then
	if ($argv[1] != "-help")then
		echo "ERROR: Could not find the file $argv[1]. Exiting..."
		exit 1
	else
		echo "User Manual will be printed on how to use this tool"
		exit 1
	endif
else
	tclsh vsdsynth.tcl $argv[1]
endif
'''

<img width="664" alt="image" src="https://github.com/prajeet-kulkarni/TCL_Prajeet/assets/121448549/ebf8d1a8-df0d-4b77-986c-da7736868304">
