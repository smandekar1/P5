# Linux Server Configuation

# Project Overview
a baseline installation of a Linux distribution on a virtual machine

# URL for hosted application 
The Restaurant Menu Application is hosted at http://52.11.229.28

# Login instructions 
At the terminal, use the command `ssh -i ~/.ssh/udacity_key.rsa grader@52.11.229.28 -p2200`    
password: grader

# Software used, installations and configuration changes 
UFW was enabled and configuration was changed per project instructions   
Time Zone via tzdata was changed per requirements   
Apache2 web server was installed   
Python-setuptools  
Python-dev   
mod-wsgi from Apache  
Git was installed in order to transfer my application to the server  
Virutalenv   
Flask - installed to run with Restaurant Menu flask app  
httplib2   
requests   
oauth2client   
sqlalchemy  
psycopg2   
Postgresql - for creating application database   


# Resources 
Steuken - https://github.com/stueken/FSND-P5_Linux-Server-Configuration

