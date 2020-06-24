# LIF-Creator

LIF Creator - LEGO Digital Designer LIF creation tool.

Copyright (C) 2020 sttng

You accept full responsibility for how you use this program.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.





LIF Creator is a command line utility for creating LIF files similar
to those found in LEGO Digital Designer. It will create a lif archive 
of all files  contained inside a folder and its subfolders, on the folder 
it was called on. The LIFCreator.py file requires a python installation
to run. The Python script has been tested to work on Python versions 2.7 
and 3.8 on macOS and Windows 10.

To create a LIF file, pass the path to a folder you want to archive
as command line argument to the program. 

This program was created to allow for interoperability with the LEGO
Digital Designer formats. In order to properly modify the LEGO Digital
Designer formats, it is necessary to repackage data contained with
the LIF file archives.
