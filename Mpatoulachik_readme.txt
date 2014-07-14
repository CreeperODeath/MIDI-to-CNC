
How to use:
Run Convert_with_GUI.py
Some windows will appear and ask you your machine type, what midi file to convert and what location/name your gcode file should have
The verbose option will print the whole midi parsing process

There seems to be a bug that makes the input windows appear behind other windows. So if nothing happens, try minimizing some stuff...

IMPORTANT: For some reason you can't have spaces in your path and filename otherwise it trhows an error...
For example C:/.../Test folder/... will not work. But C:/.../Test_folder/... will be ok.
Same with filenames like "test midi.mid" that will not work while "test_midi.mid" will.

Also using python to start a windows commandline that starts a python script feels wrong...