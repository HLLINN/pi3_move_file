# Moving files automatically every five minutes on Raspberry Pi3 B+

### STEPs:

**1. Create a python program "pi3_move_file.py"**

**2. `$sudo crontab -e` Then add a line of script: `*/5 * * * 0-6 /usr/bin/python3 /home/pi/pi3_moving_file/pi3_moving_file.py`**

**3. The last step is that: restart your Raspberry Pi3 to test the working status of this function.  `$sudo reboot`**

**4. It will show like this**
![image](picture or gif url)
ex:![movefile](https://github.com/HLLINN/pi3_move_file/movefile.gif)


### Reference:

**1.[Moving specific file types with Python](https://stackoverflow.com/questions/23556040/moving-specific-file-types-with-python)
<br/>
2.[Moving all files from one directory to another using Python](https://stackoverflow.com/questions/41826868/moving-all-files-from-one-directory-to-another-using-python)
<br/>
3.[Create a folder with Python](https://gist.github.com/keithweaver/562d3caa8650eefe7f84fa074e9ca949)
<br/>
4.<https://thispointer.com/how-to-create-a-directory-in-python/>
<br/>
5.[Creating and Deleting Directories with Python](https://stackabuse.com/creating-and-deleting-directories-with-python/)**
<br/>


