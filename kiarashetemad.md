1.

scp C:\Users\kiarash\Desktop\kiarashetemad.txt pi@raspberrypi.local:/home/pi


**2. What command do you use to see a directory listing that includes the permissions of the files?**

ls -l

**3.**

ls -l >> pr1.txt

**4. What are the permissions of the file you just created?**

rw-r--r-- 

**5. What command do you use to display the folder you are currently working from?**

pwd

**6.**

chmod g=x rs1.txt

**7.**

mkdir midtermExam-301


**8. What are the permissions of this new folder  ?**

rwxr-xr-x

**9. What command do you use to list the ports your raspberry pi is listening to? Try it using the `-at` flag.**

netstat -at

**10.**

netstat -at >> pr2.txt

**11.**

sftp pi@raspberrypi.local

**12.**

put C:\Users\kiarash\Desktop\midtermPi.txt

**13.** What does the command do?

it does two jobs. it runs pwd and put the result in a file called 'mt.txt', and after that it runs tree -l to create a tree of the current folder at puts its result in a file called 'pr.txt'.

**14.**

sudo useradd kiarashetemad

 **15.**

sudo mkdir /home/kiarashetemad
sudo chown kiarashetemad:kiarashetemad /home/kiarashetemad/

**16.**

sudo apt-get update

sudo apt-get install filezilla
