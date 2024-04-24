#Git guide
#Directory commands
mkdir [Name] --(to run in cmd, to create a new directory with the name suffixed)
cd [Name]--(to change directory to the name suffixed)

#To clone the project repository:
git clone [https url] [project name] Note:(project name given is optional), (if given it will create a new project folder with that name), (either way we can create the folder first in our local machine then clone the project)

#After coming to the project repository folder, run these commands:
git status
git add [file name] or [.] to stage all the files
git commit -m "Message to be put"
git push -u origin main
git pull
