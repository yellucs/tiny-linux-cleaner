<!DOCTYPE html>
<html>
<body>
    <h1>Tiny Linux Cleaner (TLC)</h1>
    <p>
    Update/upgrade and clean your Linux based PC with this tiny script. TLC will perform Linux apt fixes automatically to easily recover from a system crash. It will also update repositories, upgrade your packages, and even remove any unused packages.
    Requirments For Python Version:
    
        Python3
    </p>
           
    $ sudo apt-get update
    $ sudo apt-get install python3 -y
    
    <h3>Download & Run Python Version Using Git</h3>
    
    $ git clone https://github.com/yellucs/tiny-linux-cleaner.git
    $ cd tiny-linux-cleaner
    $ python3 tlclean.py 
    
    <h3>Shell Script Version</h3>
    
    $ git clone https://github.com/yellucs/tiny-linux-cleaner.git
    $ cd tiny-linux-cleaner
    $ sudo chmod +x tlclean.sh
    $ ./tlclean.sh
    
    <h3>Alternative Download Method</h3>
    
    $ wget https://github.com/yellucs/tiny-linux-cleaner/raw/master/tlclean.py
    $ python3 tlclean.py 
    
    $ wget https://github.com/yellucs/tiny-linux-cleaner/raw/master/tlclean.sh
    $ sudo chmod +x tlclean.sh
    $ ./tlclean.sh
    
    <h3>When to use</h3>
    
        Run the script when you would like to update/upgrade/clean your Linux based system.
        When your system has crashed during an update
    
    <h3>Cautions</h3>
    
    DO NOT set the script to autorun, while it is designed to be automatic it should not be run unattended. The time for TLC to finish depends on your system specifications; internet speed and amount of pending updates. If you encounter any errors re-running the script after it first stops should correct it :)
</body>
</html>