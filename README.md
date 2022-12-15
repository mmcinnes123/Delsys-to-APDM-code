# Delsys-to-APDM-code
 
Code to 'copy and paste' quaternion data from a Delsys IMU file format into a APDM template file. The APDM template is a format which can be read by an OpenSim command, which then converts it into a .sto 'oreintations' file. 
Each folder can be used depending on whether data was collected from 1, 2 or 3 sensors. 

The Matlab script with postfix 'Rearrange_xyz' allows you to post the x, y, and z quaternions into a different column in the APDM file - therefore 'renaming' them, and changing the way the orientation data is read into OpenSim.