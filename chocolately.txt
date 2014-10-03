@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

# tools
choco install dropbox
choco install gow
choco install googledrive

# graphics
choco install inkscape
choco install colorpic
choco install blender
choco install gimp 

# IDEs
choco install eclipse
choco install VisualStudio2012Professional

# editors
choco install atom
choco install lighttable
choco install ProgrammersNotepad

# browsers
choco install firefox
choco install GoogleChrome

# languages
choco install jdk8
choco install lein
choco install groovy
choco install python
choco install ruby

# build
choco install ant
choco install gradle
choco install maven
choco install puppet
choco install wixtoolset

# servers
choco install nodejs.install
choco install Tomcat

# databases
choco install mysql
choco install mysql.workbench
choco install toad.mysql


# scm
choco install git.install
choco install TortoiseGit
choco install GitHub
choco install svn
choco install tortoisesvn
choco install ankhsvn
