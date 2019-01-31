# slit
A little better cut.  The unix command cut doesn't effectivly delimeters, to combat this I wrote slit.  

Uses stdin or filenames as commandline arguments options are below

parser.add_option("-f", "--fields", dest="fields", help="a comma separated list of delimeters")
parser.add_option("-d", "--delim", dest="delim", help="the delimeter that separates column")
parser.add_option("-o", "--out", dest="out", help="the delimeter to use for output")
parser.add_option("-q", "--quote", dest="quote", help="the value that separates column")

