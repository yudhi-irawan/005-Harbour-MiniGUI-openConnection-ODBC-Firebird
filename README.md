<h2>📫 005-Harbour-MiniGUI-openConnection-ODBC-Firebird</h2>


 💞️💞️💞️<span class="font-weight-bold">Prepare | Download | Action</span>💞️💞️💞️
 <br>
<br>
<pre>
create directory: c:\git_repo\
goto: c:\git_repo\
run CMD
c:\git_repo\git clone https://github.com/yudhi-irawan/005-Harbour-MiniGUI-openConnection-ODBC-Firebird.git
c:\git_repo\cd 005-Harbour-MiniGUI-openConnection-ODBC-Firebird
dir

run vscode or your favourite editor
code .
open new terminal
</pre>
download:<br>
<span class="font-weight-bold">Current version Harbour+MiniGUI: </span>
<i>	
<a href="https://www.hmgextended.com/download.html">https://www.hmgextended.com/download.html</a>
</i>
<br>
<span class="font-weight-bold">Borland C++ Compiler version 5.8: </span>
<i>	
<a href="https://www.hmgextended.com/files/MISC/bcc582.zip">https://www.hmgextended.com/files/MISC/bcc582.zip</a>
</i>
<br>
<span class="font-weight-bold">database server for windows x64 at: </span>
<i>	
<a href="https://www.firebirdsql.org/en/firebird-5-0#windows-x64">https://www.firebirdsql.org/en/firebird-5-0#windows-x64</a>
</i>
<br>
<span class="font-weight-bold">Windows installation package - Firebird ODBC Connector at: </span>
<i>	
<a href="https://github.com/FirebirdSQL/firebird-odbc-driver">https://github.com/FirebirdSQL/firebird-odbc-driver</a>
</i>
<br>
<span class="font-weight-bold">SQL Manager for MySQL: </span>
<i>	
<a href="https://www.sqlmanager.net/products/mysql/manager">https://www.sqlmanager.net/products/mysql/manager</a>
</i>
<br>
<pre>
-1-
install Harbour+MiniGUI at: c:\MiniGUI
if exist c:\MiniGUI --> rename first to c:\MiniGUI-old


-2-
extract Borland C++ Compiler version 5.8 (bcc582.zip)
to c:\Borland\BCC58


-3-
install database server: Firebird-5.0.2.1613-0-windows-x64.exe
at: C:\Program Files\Firebird\Firebird_5_0
SYSDBA Password: masterkey
Retype SYSDBA Password: masterkey
install


-4-
install Firebird ODBC Connector:
extract win_installers.zip
Firebird_ODBC_3.0.0.16_Win32.exe --> i use this file!
installed in your PC


-5-
install SQL Manager for MySQL:
extract file ibmanager_x64.zip --> IBManagerFull-x64.msi
installed in your PC
run

Register Host:
Host name: localhost
Use name: SYSDBA
Password: masterkey
Security DB: C:\Program Files\Firebird\Firebird_5_0\security5.fdb
Client Library: C:\Program Files\Firebird\Firebird_5_0\fbclient.dll
Next
Path to database utilities: <empty>
Run

Create database:
Checked Database will be created on the host already registered in SQL Manager
Host name: localhost
User name: SYSDBA
Password: masterkey
Client library: C:\Program Files\Firebird\Firebird_5_0\fbclient.dll
Next
Fullly qualified database file path: c:\git_repo\005\mcg_db.fdb
Next
Run
Test Connection --> must be: Connected!
OK

Create table and insert data:
double click MCG_DB on localhost
goto menu Tools-Execute Script
open with your editor file: tblAbsenceType.sql
copy and paste to Execute Script editor
click Execute Script
Disconnect form database


-6-
compile.bat
run demo1.exe

</pre>

other reference: 
<br><br>
 
 
 Thanks you. 

 👋 👀 🌱 💞️ 📫 