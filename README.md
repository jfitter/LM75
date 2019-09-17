## Arduino Library for the LM75A Temperature Sensor

This library was written to enable remote sensing of the temperature of batteries and motor controllers used in remotely piloted aircraft, for the purpose of real time data logging and air to ground telemetry.


This sensor uses the I2C bus protocol to communicate allowing the Arduino standard Wire library to communicate with the device. 2 pins are required to interface the device to an Arduino - the SDA and SCL lines.

### Installing

Download the distribution package and decompress it.  
Rename the uncompressed folder ***/lm75***.  
Check that the ***/lm75*** folder contains the following files;

> LM75.cpp  
> LM75.h  
> LM75.chm  
> LM75.pdf  
> property.h  
> doxyfile  

Place the ***/lm75*** library folder into your ***arduinosketchfolder/libraries/*** folder.  
You may need to create the libraries subfolder if its your first library.
Restart the IDE.

### Documentation

*LM75.chm* and *LM75.pdf* contain the documentation for the classes.  
A Doxygen script is included to enable generation of documentation. You will need the graph tool, the dot tool, and the help compiler, in addition to editing the paths to these tools in the script to suit your environment. 

### Author

John Fitter B.E., Eagle Air Australia Pty. Ltd.  

### License

This program is licensed under the terms of the GNU Lesser General Public License as published by the Free Software Foundation. See the GNU Lesser General Public License for more details at <http://www.gnu.org/copyleft/gpl.html>

