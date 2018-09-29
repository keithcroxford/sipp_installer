# sipp_installer
The purpose of this script is to streamline the installation of SIPp on Ubuntu 16.04. Normally, there are many dependencies that must be satisfied before SIPp can be installed. This can be extremely frustrating and time consuming. This script will take care of that. 

#Instructions 
1. Download / clone the script. 
2. Set permissions with chmod
-- sudo chmod +x sipp_installer.sh
3. Run the script as sudo 
-- sudo ./sipp_installer.sh 
4. The script will install to /opt/sipp3-3/ and create a symbolic link to /usr/local/bin to simplify running of the tool.
5. This will also clone a great repo of scenarios to /opt/sipp3-3/sipp-scenarios

Enjoy! 
