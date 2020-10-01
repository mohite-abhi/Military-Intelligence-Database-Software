# MilitaryIntelligenceSoftware

<b>Introduction</b>
Design and implement mySQL database and create UI to query, edit and display data using Python. This is a mysql project implemented with the help of python tkinter for ui.

<b>Steps followed for creating the project</b>

1. Identify the data required such as list of people’s names,
addresses, dob, list of organizations etc. and create table
formats for them.
2. Identify relations between those tables if any and make
an er diagram using this data.
3. Try to remove any redundancy and normalize the er
diagram.
4. Design an user interface prototype on paper/ paint
program on computer to finalize the UI.
5. Design the tables in mysql and decide foreign keys
according to er diagram.
6. Design the UI using tkinter in python and then connect
them using mysql connector.


<b>Let’s build</b>
Run this .py file with internet turned on, after reading
below steps :<br>
https://drive.google.com/file/d/1FlTJ_uL8k-yzM3rOdMdSlk
ZYtqJG_bY4/view?usp=sharing (size 77kb)<br>
<br>
Running the python file shared above will launch the
software, if your internet is 
connected and you have python installed in your system along
with the following python library  dependencies:<br>
- tk or tkinter<br>
- python-mysql-connector<br>
- pillow<br>
- numpy<br><br>
You can install these libraries with help of pip on
windows/linux/macos. (mysql connector is installed with
package manager in tested arch based linux machine)<br><br>
Our mysql database temporarily hosted online at
https://www.freemysqlhosting.net, if it is expired then this
won’t work, so in that case use this .sql file to import the
database somewhere<br>
https://drive.google.com/file/d/1_DX59FUJD8wmMUoKzv2Zx_X7xTg9Ty3I/view?usp=sharing<br>
and then change these variables inside .py file to your
own credentials.<br>
18
 globalhost = "sql12.freemysqlhosting.net"<br>
19
 globaluser="sql12352363"<br>
20
 globalpwd="qssD26v9uQ"<br>
21
 globaldb="sql12352363"<br>
