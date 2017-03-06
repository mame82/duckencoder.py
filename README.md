Python port of infamous of hak5 DuckEncoder
by MaMe82

    Duckencoder python port 1.0 by MaMe82
    =====================================
    
    Creds to:	hak5Darren for original duckencoder
    		https://github.com/hak5darren/USB-Rubber-Ducky
    
    Converts payload created by DuckEncoder to sourcefile for DigiSpark Sketch
    
    Usage: python duckencoder.py -i [file ..]			Encode DuckyScript source given by -i file
       or: python duckencoder.py -i [file ..] -o [outfile ..]	Encode DuckyScript source to outputfile given by -o
    
    Arguments:
       -i [file ..]	Input file in DuckyScript format
       -o [file ..]	Output File for encoded payload, defaults to inject.bin
       -l <layout name>	Keyboard Layout (us/fr/pt/de ...)
       -h		Print this help screen

