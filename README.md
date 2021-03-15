# InputFileElectronTest

Since electron 10.1.6 the filechooser from the input file do not re-open at the previous picked files location. Way to reproduce:

1. git clone https://github.com/Javanatole/InputFileElectronTest.git
2. npm install.
3. npm start, wait for the ui to show up.
4. Click on "Choisir un fichier" and select a picture in one directory, the name of the choosen file will be displayed.
5. Re-Click on "Choisir un fichier", the file chooser do not reopen at the previous picked file location.

It's working in electron version 10.1.5
