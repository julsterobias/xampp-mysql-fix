# Ver 0.0.1 fetus

# XAMPP MySQL shutdown unexpectedly FIX

## What it will do?
- Rename the "data" folder to "data-bat-temp"
- Copy the backup folder and rename it to "data"
- Copy your database folder and idata1 file from "data-bat-temp"
- Paste the files to your new "data" folder
- Rename the "data-bat-temp" to "data-{timestamp}"

## Setup
- Copy the mysqlfix.txt and paste to xampp/mysql folder
- Edit the mysqlfix.txt, find the the {database-folder}
- Change the extension of the file to .bat
- Run and .bat file and run again your mySQL
- Continue coding
