NOTE! This is not my own work. This is a fork of diimdeep's code with some pullrequests and my own adjustments added.
All credit goes to respective person.


VisualStudioFileOpenTool
========================

Tool that trying open specified file at spicified line in active Visual Studio   


[Download binary](https://github.com/diimdeep/VisualStudioFileOpenTool/blob/master/VisualStudioFileOpenTool/bin/Release/VisualStudioFileOpenTool.exe)


	usage: <version> <file path> [line number] [column number]

	Visual Studio version                 value 
	VisualStudio 2002                     2 
	VisualStudio 2003                     3 
	VisualStudio 2005                     5 
	VisualStudio 2008                     8 
	VisualStudio 2010                    10 
	VisualStudio 2012                    12 
	VisualStudio 2013                    13 
	VisualStudio 2015                    15 
	VisualStudio 2017                    17 
	VisualStudio 2019                    19 


GrepWin settings:

	VisualStudioFileOpenTool.exe 12 %path% %line%
	
Beyond Compare settings(Options - Open With - Command line):
	
	VisualStudioFileOpenTool.exe 12 %f %l
	
Inspired by http://stackoverflow.com/questions/350323/open-a-file-in-visual-studio-at-a-specific-line-number


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/diimdeep/VisualStudioFileOpenTool/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

