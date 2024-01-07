This part of the project is all about PERMISSIONS, using and mastering commands such as: 

0- su 
1- whoami
2- groups
3- chown
4- touch

From here on the syntax gets complicated, so I'll provide the whole command

5- chmod u+rwx hello
6- chmod ug+x,o+r hello
7- chmod +x hello
8- chmod 007 hello
9- chmod 753 hello
10-chmod --reference=olleh hello
11-chmod -R -X .
12-mkdir -m 751 my_dir
13-chgrp school hello
14-chown -R vincent:staff ./*(ignoreme)* 
15-chown -h vincent:staff hello (include an underscore before hello pls)
16-chown --from=guillaume vincent hello
