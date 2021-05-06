**Steps for SB Serial Servo software installation:**

1. Open Terminal and download the code by writing:
```git clone https://github.com/pavansai018/servo-motor-gui.git```

2. Your code will be downloaded to '/home/pi' directory. Use 'ls' command to check the list of directories.

3. Go to directory 'servo/gui' and run the command to change the permissions of 'configGUI' python files:
   ```
   sudo chmod +x configGUI.py
   ```
4. To run the GUI use the following command:
   ```
   ./configGUI.py
   ```
   
   ### New Updated GUI with automatic detection of COM ports 
   
   * To use updated GUI, you need to install a library tk-tools , to install it run below command.
   
   ```
   pip3 install tk-tools
   ```
   
   * Now you can directly run "Updated_ConfigGUI.py" from user interface or by running below command
   
    ```
   python3 Updated_ConfigGUI.py
   ```
