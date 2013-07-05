VisualStudioFileOpenTool
========================

Tool that trying open specified file at spicified line in active Visual Studio

Inspired by http://stackoverflow.com/questions/350323/open-a-file-in-visual-studio-at-a-specific-line-number

	usage: <version> <file path> <line number> 

	Visual Studio version                 value 
	VisualStudio 2002                     2 
	VisualStudio 2003                     3 
	VisualStudio 2005                     5 
	VisualStudio 2008                     8 
	VisualStudio 2010                    10 
	VisualStudio 2012                    12 


GrepWin settings example:

	VisualStudioFileOpenTool.exe 12 %path% %line%