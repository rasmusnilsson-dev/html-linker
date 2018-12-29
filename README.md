# html-linker
A simple script to link .css and .javascript files to an output of .html.

## Usage
Create a .pth file and fill it with regular html code apart from a <css/> tag where you want your css links and a <javascript/> tag where you want your javascript links. Then put all of your .css files you'd like
to be linked in a 'css' directory, then do the same for .js files with a 'javascript' directory. 

Run the script from the command line use the format:
python linker.py inputfile.pth outputfile.html
